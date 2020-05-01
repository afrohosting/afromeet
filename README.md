# Afro Meet - Secure, Simple and Scalable Video Conferences

Afro Meet is an open-source (Apache) WebRTC JavaScript application that uses [Jitsi Videobridge](https://jitsi.org/videobridge) to provide high quality, [secure](#security) and scalable video conferences.

The Afro Meet client runs in your browser, without installing anything else on your computer. You can try it out at https://afromeet.cl

Afro Meet allows very efficient collaboration. Users can stream their desktop or only some windows.

### Mobile apps

* [Android](https://play.google.com/store/apps/details?id=cl.afro.meet)

[<img src="resources/img/google-play-badge.png" height="50">](https://play.google.com/store/apps/details?id=cl.afro.meet)

* [iOS](https://itunes.apple.com/cl/app/afromeetios/id1509073357)

[<img src="resources/img/appstore-badge.png" height="50">](https://itunes.apple.com/cl/app/afromeetios/id1509073357)

## Security

WebRTC does not (yet) provide a way of conducting multi-party conversations with end-to-end encryption. 
Unless you consistently compare DTLS fingerprints with your peers vocally, the same goes for one-to-one calls.
As a result, your stream is encrypted on the network but decrypted on the machine that hosts the bridge when using Jitsi Meet.

The Afro Meet architecture allows you to deploy your own version, including
all server components. In that case, your security guarantees will be roughly
equivalent to a direct one-to-one WebRTC call. This is the uniqueness of
Jitsi Meet in terms of security.

The [Afro Meet](https://afromeet.cl) service is maintained by [Afro Hosting](https://www.afro.hosting).

## Security issues

We take security very seriously and develop all Afro projects to be secure and safe.

If you find (or simply suspect) a security issue in any of the Afro projects, please send us an email to admin@afro.cl.

**We encourage responsible disclosure for the sake of our users, so please reach out before posting in a public space.**
