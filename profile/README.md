# Spotty For Alice 
<img 
	src="https://user-images.githubusercontent.com/55200686/168448665-76ee97ab-5261-4688-9808-0fa83f5d25db.png" 
	height="200"
/> 

Yes, we have dansing *Mike Wazowski* as a logo!
##  The Pain (not actual since 02.24.2022)
A user story: you use Spotify as the main music service on your smartphone and desktop but you also have a Yandex.Station with Alice smart helper. The pain is the lack of synchronization between playlists in two music services, that’s why you can’t listen to his freshest favorite music in your smart pod. *Spotty For Alice* is a service for migrating music tracks from various music services (worked with Spotify only) to Yandex.Music, which plays tracks by commands to Alice voice assistant.
##  How it works? (Arhitecture)
<img 
	src="https://user-images.githubusercontent.com/55200686/168449126-d5a2d635-4aee-4779-8ba4-ba2ee12d0150.png" 
	height="600"
/>

You should start Telegram bot where you should authorize to Spotify (via OAuth 2.0) and Yandex.Music (sorry, but enter login and password). You also need to do simple authorization in Yandex.Dialogs (write your email address). It's necessary to link id from Alice with Yandex.Music id (yes, they are different).
Then you can query playlists from Spotify and choose one to migrate tracks from it to Yandex.Music. And, after the migration end, you can listen to new music in Yandex. 

##  Do you have better ideas? 
Write to us. We want that our project worked not only in test mode...
