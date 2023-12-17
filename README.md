# CTF 1 : writeups

Owner: Tarek Dhokkar
Created time: December 5, 2023 10:38 AM

## Welcome to the first MINI INTRO CTF SECURINETS ISITCOM

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled.png)

### Flag : securinets{ . . . }

## challange 1 : Welcome

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%201.png)

This is the first simple challange all u need to do just to copy paste the flag in the prompt

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%202.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%203.png)

And Boom you solved the easy one:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%204.png)

# OSINT CTF’s:

In the context of Capture The Flag (CTF) competitions, OSINT (Open Source Intelligence) challenges involve gathering information from publicly available sources to solve a puzzle or answer a question. The goal of OSINT challenges in a CTF is to encourage participants to use their investigative and research skills to find hidden or obscure information.

## Type Easy - 7amess writeup:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%205.png)

So we need to know what this shit! so let’s do some searches

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%206.png)

Someone by the name of Abou Obeida made this statement okay so let’s return to search for the correct english name

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%207.png)

okay so let’s try to submit the name:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%208.png)

oh shitttt

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%209.png)

Incorrect let’s try to remove the “ “ and replace it with “_”

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2010.png)

And boom. Correct Flag and 7amess Done!

 

## Type Med - Easy Maps Writeup:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2011.png)

so “Hotel l3ayechy” what hotel l3ayechy means ! in the “Nuit d’info” Spot i see this

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2012.png)

Okay! ISITCOM huh let’s get the ISITCOM latitude and longitude From “Google Maps”.

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2013.png)

okay we get this 35.8579346,10.596439 and in the description he wont only 2 numbers before and after the comma for the latitude and longitude

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2014.png)

so we need only this : 35.85,10.59 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2015.png)

and Yeahhh Correct Flag :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2016.png)

## Type Hard : Social Media :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2017.png)

okay i think that he want to see the postes shared yesterday nothing shared yesterday only this :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2018.png)

Okay let’s download the image and see what we can found on it, so first nothing showing in plain text and also he said this :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2019.png)

so this picture hiding something let’s try with exiftool to show the image METADATA :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2020.png)

let’s try to submit

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2021.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2022.png)

easy peasy lemon squeezy😎

# Forensics

## type easy : ExifMe

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2023.png)

something is hidings in the cat3.png let’s download the file and show we can discover the name of challenge so attractif let’s try with exiftool

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2024.png)

okay maybe this is the flag let’s try to submit it:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2025.png)

Oh F*ck Fake Flag! let’s return to the METADATA

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2026.png)

I think this is a Base64 encoded let’s try to decode 

i use this website to decode Base64 encode : [https://www.base64decode.org/fr/](https://www.base64decode.org/fr/)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2027.png)

Is this the flag! let’s try to submit

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2028.png)

Yeah we got it!!

## type Med : Stegno Noobies

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2029.png)

He said Outside the Box Huh! okay let’s download the file and see what we can find!

Let’s try with exiftool 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2030.png)

Nothing hiding her

let’s open the image 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2031.png)

Huh the picture so attractive some folders and pictures hidings in this picture!

okay let’s try to unzip it 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2032.png)

Oh LOL we have  some folders and a picture hidings inside the original picture okay let’s find the Palestine.jpg image and open it.

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2033.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2034.png)

is this the flag! 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2035.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2036.png)

Yes we solve it!!!

## Type Med : Spectre

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2037.png)

okay something hided int the mp3 okay let’s download the audio file and discover the hiddings in this challange u can use :

Audacity in Windows you can download it from this link : [https://github.com/audacity/audacity/releases/download/Audacity-3.4.2/audacity-win-3.4.2-64bit.exe](https://github.com/audacity/audacity/releases/download/Audacity-3.4.2/audacity-win-3.4.2-64bit.exe)

or i recommend u to use Sonic Visualizer in Linux or Windows u can install it with this command:

```java
sudo apt install sonic-visualiser
```

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2038.png)

So let’s solve this challenge with Audacity and Sonic

First Audacity:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2039.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2040.png)

let’s open the file 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2041.png)

The Name of challenge Spectre so let’s open the spectrogram of the audio

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2042.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2043.png)

click Spectrogram button 

What’s Spectrogram : 

A spectrogram is a visual representation of the spectrum of frequencies in a sound or other signal as they vary with time. In the context of CTF (Capture The Flag) challenges, a spectrogram may be used to hide information within an audio file. This is often referred to as audio steganography. The challenge might involve extracting hidden messages, images, or other data that have been encoded within the audio file's spectrogram.

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2044.png)

okay let’s play the music and zoom in the spectrogram to see if we can see anything:

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2045.png)

Yeah i Found the flag ! securinets{w3_l0v3_ISITCOM}

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2046.png)

Yeah Correct <3 !!

OKAY now let’s do the same with sonic-visulaiser :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2047.png)

Open the audio file and select “Layer”

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2048.png)

Now, Select Add Spectrogram ⇒ All Channels Mixed

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2049.png)

Okay let’s try to zoome in and out to find the flag u cand zoome with this bar :

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2050.png)

And Yeah we got it 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2051.png)

Easy!!

# CRYPTO

## Type Easy : Welcome Crypto

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2052.png)

it’s a binary code let’s try to convert as ASCII or TEXT

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2053.png)

This is the best Website for converting , Link : [Binary to Text Translator (rapidtables.com)](https://www.rapidtables.com/convert/number/binary-to-ascii.html)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2054.png)

Very Easy! Flag : securinets{w3lc0m3_t0_crypt0_w0rld}

## Type Easy : Base—

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2055.png)

okay what’s this ? c2VjdXJpbmV0c3tCNHNlNjRfdjNyeV8zNHN5fQ==

let’s try to define it 

i will use this website to identify the cypher Link : [Decrypt a Message - Cipher Identifier - Online Code Recognizer (dcode.fr)](https://www.dcode.fr/cipher-identifier)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2056.png)

this website tool is the best in any type of challenges

 

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2057.png)

So it’s a Base64 Coding okay let’s try to decode it

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2058.png)

okay now we will use the base64 decoder for the same website here is the Link : [Convertisseur Base64 - Décoder, Encoder, Convertir Base 64 en Ligne (dcode.fr)](https://www.dcode.fr/code-base-64)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2059.png)

And we found it, Flag : securinets{B4se64_v3ry_34sy}

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2060.png)

## Type Med : Crypto Noobies

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2061.png)

Okay let’s download the file

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2062.png)

Oh shit it’s a binary very easy let’s convert it to text

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2063.png)

Okay it seems like Hexadecimal ! okay let’s convert it to text

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2064.png)

Okay it’s another face with Base64 encode okay let’s decode it

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2065.png)

And yeah this is the flag : securinets{Crypt0_N00b13s_Ch4ll4ng3s}

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2066.png)

## Type Hard : RSA is Simple

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2067.png)

okay let’s download the file

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2068.png)

okay let’s use RsaCtfTool u can download it with this command

```java
git clone https://github.com/RsaCtfTool/RsaCtfTool
```

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2069.png)

First cd to Directory and install all the requirements

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2070.png)

after downloading all the requirements do this

```java
./RsaCtfTool.py -n 1422450808944701344261903748621562998784243662042303391362692043823716783771691667 --decrypt 173472922811303101466694799968072059451419729302896538084853387816118546655495409 -e 65537
```

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2071.png)

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2072.png)

And yeah we got it the flag is : securinets{RSA_1s_g0od_00264570}

![Untitled](CTF%201%20writeups%20daa6b7f1112f4a8bbf103a0cf5c2bf95/Untitled%2073.png)

# Bye Bye !
