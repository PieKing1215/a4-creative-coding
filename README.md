## Music Maker

https://a4-david-mahany.glitch.me/

![preview](demo.png)

- The site allows you to make simple pieces of music and share them by copy pasting a code (or the URL if it's short enough).
- The functionality is entirely client side, and any stored data is in localStorage - no data is stored on the server, it just exists to serve files.
- I made heavy use of the WebAudio and Canvas APIs for playback and rendering.
- I used [Tweakpane](https://cocopon.github.io/tweakpane/) for some UI things.
- I used a slightly modified version of the [JSONCrush](https://github.com/KilledByAPixel/JSONCrush) library for json string compression.
- I used [Intro.js](https://introjs.com/) for the tour/help dialogue, which should explain the UI and controls.

Below are some sample song codes:<br>
The first is based on an original song I made a few years ago, and the second is a transcription of the intro of "Attack of the Killer Queen" by Toby Fox.<br>
(see [samples.txt](samples.txt) if copying from here doesn't work)
```
('m!8~b!200~i![('m!'LeadTsquareJ0CV5F1XD59M43GF1.D56M68GF1W-V59,2CV61R2D59R43GF3.D56R68GF3W-V52,4CV54O2D61O43G9OD5F5.68G9O7D5F5.93G9,6C*6Y6WD62,7C187*6Y7XD59,7.43GF7.D56,7.68GF7W-V59UPulseTsawtooth'y0CZC2Q--ZC7j1CZM2j1.-ZM7j2CAz2XQF2.Qz2WQF3CA0R2QF3.Q0R7QF4CZ,4Xj4.-Z,4Wj-ZO2j5.-ZO7j6CAz6XQF6.Qz6WQF7CAY7XQF7.QY7WQ7UBassTtriangle'y0M*26MD26M687DV1xF2M*28RD28R687DV3x8,4M*26OD26O687DV5xF6,Y28,FY29EKickTd_kickJ0p1p1Xj2p3p3Xj4pj5Xj6p7p7XQ5ESnareTd_snareJ0.N1.j1WN2.N3.j3WN4.N5.j5WN6.N7.j7W-37*45EHatTd_hatJ0X-1A-7I1XI1WI2XI2WI3XI3.I3WI4XI4WI5XI5WI6XI6WI7XI7.I7W-1A5EidkTd_fallJ4C*43,0C*43])])*5,-*0.AV4C,0.D-187*EU[] F7,G7-06V5I-1A*J'~v!1yM,1.N-37*4*O,5.Q-AR,3.T'~t!'U]),('m!'V2*W.7X.2Y1,ZV38jQ*pCA*x.87-1V2y~n![z0,%01zyxpjZYXWVUTRQONMJIGFEDCA-*_
```

```
('m!8~b!140~i![('m!'Lead'~v!0.6000000000000001~n![0.0UJEPJ4CqJE2xC3PJERJ4C4RJEE3PS2G0UT0GPxGqJ7G2xG3PT0GRT-1.4RT3GE3PS2F0UT0FPxFqJ7F2xF3PT0FRT-2.4RT3FE2S2F7E2S0,3CRS2MRT0M4RxMEO7M7EPS0DCPS2VPT0VqE3PS2VEPS0VUxV6QEPS0V8PJ3VQJf.9RJXE1O8IPJ7IqEqf8IRE1OS.E1O7IUp6QEqf4IQE1OX6Cqf8l.qEqfX6.RERf-7Cf-7.Ef4C0UT7CPT6CqT7C2*60C3PT7CRT6C4RT7CE3P-64G0U*UGP*60GqT9G2*60G3P*UGR*67G4R*6-1.E3P-64F0U*UFP*60FqT9F2*60F3P*UFR*67F4R*6-2.E2-64F7E2-U,3CR-64MR*UM4R*60ME2S9M7EP-UDCP-64VP*UVqE3P-64VEP-UVU*60V6QEP-UV8PTf.QT7V9RT9,EP-60IPT9IqEq-60IREPS7IEPS9IUT7I6QEqS6IQEPS9lCq-60l.qEqS9l.RERSX7CSX7.ES6gBass'~t!'sawtoothjC0U-21CPu1C2u1CRu1Cu1CUu1C7u1CQu3,1C0U-24GPu4G2u4GRu4Gu4GUu4G7u4GQu4,2C0U-17FPr7F2r7FRr7Fr7FUr7F7r7FQrX0YEPJE2JERJEJEUJE7JEQJX1Y8GPxG2xGRxGxGUxG7xGQx,2Y1FPJ1F2J1FRJ1F-0D1FJ1FUJ1F7J1FQJ1,3,0D-3YWPJW2JWRJWJ4MUJ4M7J4MQJ4,3C0US0MPT0M2T0MRT0MT0MUT0M7T0MQT0DC0U-21VPu1V2u1VRu1Vr9VUr9V7r9VQr9,r7IPr7I2r7IRr7Ir6IUr6I7r6IQr6l.RE-14,7C-16DC0US2VPT2V2T2VRT2VT2VUT2V7T2VQT2,T2IPT2I2T2IRT2IT2IUT2I7T2IQT2lC2S2l.RE2S0,7C2S2DY8VPxV2xVRxVJ7VUJ7V7J7VQJXpPp2pRppUp7pQJ-6C2S0l.REO-7C2S0,7.EOX7.7E"Kick'~t!'d_kickjCOEQE1O-1C1O-1.QE1O-2C1O-2.QE1O-3C1OWEOW7EOW4RJWRJfCOf.2EOf.EOf.7EO-EOS.2EOS.EOS.7EOW3PE031O3M34R-0D4M34R-0D4M34RE031"Hat'~t!'d_hatjYE2JEJE7J-1Y7G2J7GJ7G7JX3YW2JWJfYf.2Jf.Jf.7J-p2pp7JW7J-2Y4F2J4FJ4F7J4C9583N74D6C9A66CZ63D6CQEZ63D-1.9583N74D-1.9A6EZ74D6GQy7FQy4F9A6y-2.9zWRyW4A6yW4zf.9zf.9A6CZ96Df.QEZ07fS.9zS.9A6CZ96DS.QEZ07f5])])*E0U-S,A1666666666666C,0.D,4E-0.F,2.G,1.I,5.J*4M,3.N333333333333CZO2fP12Q87R37S-5T*5U62VD.W-3.X7,YC06OZ04Af-4g]),('m!'j'~v!1~n![0l,6pJS.q1Qr*1u*2xJ8yEZ52Dz58N96D"O4g[] %01"zyxurqpljgfZYXWVUTSRQPONMJIGFEDCA-*_
```
