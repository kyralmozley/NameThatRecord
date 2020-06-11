# NameThatRecord

It's a problem I'm sure all hipsters (and anyone that was alive in the 80s) has had. You're listening to a record on good old vinyl, but you don't know the name of this tune. Rather than having to get up, get your phone, and ask Siri what song is playing wouldn't it be easier if a little device next to your record player could display a Now Playing? Well here's the solution. 

Hardware used:
- Raspberry Pi 3b+
- ReSpeaker 2-Mics Pi HAT

Sadly, Shazam doesn't have an API and I haven't managed to find any alternatives... so in an ambitious turn of events I will also be building my own Shazam like service! I imagine this will involve taking the FFT of an audio clip and identifying the peaks to idenify a track. I'm then going to have to build my own dataset? I guess I can stream spotify and use their api to get the track name at the same time? Ok this sounds like a bigger project than initially thought. Lets go!
