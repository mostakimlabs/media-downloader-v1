<h3 align="center">  <p align="center">
    <img src="https://img.shields.io/badge/WELCOME%20TO-MOSTAKIM%20MEDIA%20DOWNLOADER-green?colorA=%23000000&colorB=%23017e40&style=flat-square" alt="Welcome to MOSTAKIM Media Downloader">


<p align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=26&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&repeat=true&width=500&height=70&lines=media-downloader-v1;MEDIA+DOWNLOADER+BY+MOSTAKIM;POWERED+BY+MOSTAKIM+LAB'S"
    alt="media-downloader-v1 Premium Typing Animation"
  />
</p>


</p><p align="center">
  <a href="https://www.npmjs.com/package/media-downloader-v1">
    <img alt="npm version" src="https://img.shields.io/npm/v/media-downloader-v1.svg?style=flat-square">
  </a>
  <img alt="GitHub package version" src="https://img.shields.io/github/package-json/v/mostakimlabs/media-downloader-v1?label=github&style=flat-square">
  <a href="https://www.npmjs.com/package/media-downloader-v1">
    <img alt="npm downloads" src="https://img.shields.io/npm/dm/media-downloader-v1.svg?style=flat-square">
  </a>
  <a href="https://www.jsdelivr.com/package/npm/media-downloader-v1">
    <img alt="jsDelivr" src="https://data.jsdelivr.com/v1/package/npm/media-downloader-v1/badge">
  </a>
</p><h2 align="center">📦 Installation</h2>npm install media-downloader-v1

<h2 align="center">🚀 Usage Examples</h2>Facebook & Instagram

const { ndown } = require("media-downloader-v1");

async function downloadMedia() {
  const url = "YOUR_FACEBOOK_OR_INSTAGRAM_URL";
  const result = await ndown(url);

  console.log(result);
}

downloadMedia();

TikTok

const { tikdown } = require("media-downloader-v1");

async function downloadTikTok() {
  const url = "YOUR_TIKTOK_URL";
  const result = await tikdown(url);

  console.log(result);
}

downloadTikTok();

YouTube

const { ytdown } = require("media-downloader-v1");

async function downloadYouTube() {
  const url = "YOUR_YOUTUBE_URL";
  const result = await ytdown(url);

  console.log(result);
}

downloadYouTube();

Twitter / X

const { twitterdown } = require("media-downloader-v1");

async function downloadTwitter() {
  const url = "YOUR_TWITTER_OR_X_URL";
  const result = await twitterdown(url);

  console.log(result);
}

downloadTwitter();

Facebook — Cookie-Based Downloader

const { fbdown } = require("media-downloader-v1");

const key = "MOSTAKIM"; 
const cookie = "YOUR_FACEBOOK_COOKIE";
const url = "YOUR_FACEBOOK_VIDEO_URL";

fbdown(url, cookie, key).then(console.log).catch(console.error);

Facebook — Alternative Downloader

const { fbdown2 } = require("media-downloader-v1");

const key = "MOSTAKIM"; 
const url = "YOUR_FACEBOOK_VIDEO_URL";

fbdown2(url, key).then(console.log).catch(console.error);

Google Drive

const { GDLink } = require("media-downloader-v1");

GDLink("YOUR_PUBLIC_GOOGLE_DRIVE_URL")
  .then(console.log)
  .catch(console.error);

Pinterest

const { pintarest } = require("media-downloader-v1");

pintarest("YOUR_PINTEREST_URL")
  .then(console.log)
  .catch(console.error);

CapCut

const { capcut } = require("media-downloader-v1");

capcut("YOUR_CAPCUT_URL")
  .then(console.log)
  .catch(console.error);

Likee

const { likee } = require("media-downloader-v1");

likee("YOUR_LIKEE_URL")
  .then(console.log)
  .catch(console.error);

Threads

const { threads } = require("media-downloader-v1");

threads("YOUR_THREADS_URL")
  .then(console.log)
  .catch(console.error);

All-in-One Media Downloader

const { alldown } = require("media-downloader-v1");

alldown("YOUR_MEDIA_URL")
  .then(console.log)
  .catch(console.error);

Supported platforms (depending on package implementation): Facebook, TikTok, Twitter/X, Instagram, YouTube, Pinterest, Google Drive, CapCut, Likee and Threads.


</p><h2 align="center">🌐 Connect With Me</h2><p align="center">
  <a href="https://www.facebook.com/MOSTAKIM.LABS">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">
  </a>
  <a href="https://t.me/M0STAKIM10X">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="https://github.com/md-mostakim-islam-sagor">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
