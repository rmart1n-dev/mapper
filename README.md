# mapper

Stupid side project I worked on when I had nothing to do on a flight.

Uses base62 to encode a TXT file to an .enc and a .dict file, (hopefully) deterministically.
Since I wanted the encoded file to be smaller than the input file, I decided the dict needs to go, so I hooked it up to a training loop for a minimal AI model to predict the decoded text from the .enc file.

This readme is preliminary right now because actually *haven't* done this yet, but I am now.
