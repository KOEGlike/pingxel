
# Pingpong ball matrix backpack

I'm again showing how good I am at naming things.

![wall mounted matric](https://cdn.hackclub.com/rescue?url=https://hc-cdn.hel1.your-objectstorage.com/s/v3/e008183fc50a0189_pxl_20251226_085102902-ezgif.com-video-to-webp-converter-1.webp)

## What is it?

This is a 5x10 LED matrix with pingpong ball diffusers that is wearable on your back.

## Why?

Almost from the start of my journey into electronics, I wanted to make a pingpong ball display. With Hack Club's [Alleyway](https://alley.hackclub.com) happening, I finally had a reason to make one.

## The process

I went with a pretty simple list of components:

- Xiao ESP32-C6, this basically does everything: charges the battery, controls the LED strips/matrix, and connects to your phone.
- 50 LEDs cut up from a 60 LED/m WS2812b LED strip. I glued these behind the pingpong balls.
- A 3D-printed frame that holds everything together.
- A USB power bank to power the whole thing

Originally I wanted to make a 10x10 matrix, but then I realized that 100 pingpong balls were surprisingly expensive if I wanted them to arrive in time. So I ordered 60 from a local vendor.

*Fun fact*: I ordered 100 pingpong balls from China for $3 that would have just arrived 3 days before I had to take off, so I canceled the order, not to risk them not arriving. When I arrived home, I got a package of 100 pingpong balls. Now I have 100 beer pong pingpong balls.

When designing the case, I realized that I had a really inefficient model that used up a lot more filament than it needed to. Turns out, something has already been invented that stores
spherical objects in a material-efficient way in a grid pattern. It is called an egg carton. So my new design is heavily inspired by the design of egg cartons.

I use WLED to control the matrix.

Some day I may extend the matrix to be the originally planned 10x10 variant

## Me in LA at supercon

![me](https://cdn.hackclub.com/rescue?url=https://hc-cdn.hel1.your-objectstorage.com/s/v3/09bb14006d6e19b4_pxl_20251102_015735810.jpg)
