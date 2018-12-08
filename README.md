# FXMessages
`FXMessages` is a small Java application I created to test [#118](https://github.com/javafxports/openjdk-jfx/issues/118) solutions and make demos.

It should become a communication app like Google Messages but with scientifical writing capabilities. 

![screenshot_20181031-122019_red](https://user-images.githubusercontent.com/19194678/47786391-f172a000-dd0b-11e8-9035-a3a88f1d7586.png) ![screenshot_20181031-123115_red](https://user-images.githubusercontent.com/19194678/47786411-fdf6f880-dd0b-11e8-8590-1ca412d64f28.png) ![screenshot_20181031-122218_red](https://user-images.githubusercontent.com/19194678/47786430-06e7ca00-dd0c-11e8-8444-7643fcbc8147.png) ![screenshot_20181031-123504_red](https://user-images.githubusercontent.com/19194678/47786437-0d764180-dd0c-11e8-8491-3e9ece4c72da.png) ![screenshot_20181208-180313_red](https://user-images.githubusercontent.com/19194678/49688531-05cc6880-fb14-11e8-8f91-e454d4600e70.png) ![screenshot_20181208-175241_red](https://user-images.githubusercontent.com/19194678/49688488-64451700-fb13-11e8-8828-40fb400b508c.png)

On DeskTop, I can enter signs like ∞, ∈, × , ⩽, α, ..., δ, ... ω, ..., Δ, ... but also square root, fraction, ... simply by typing `.Del` ... or `.frac` ... (Δ sign and fraction).
On Android, this doesn't works, `MathML` is disabled and `WebView ` `setOnKeyReleased` method doesn't work too due to what I previously describe.

I posted an Android apk on Play Store : [FXMessages bêta](https://play.google.com/store/apps/details?id=com.fxmessages). I do it for my own tests with Android API, JavaFX port and Play Store process. Presently, only #118 solutions are implemented. You won't find other functionnalities, I am still working on them.