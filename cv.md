# Evgeniia Shirshikova

![photo](/img/photo.jpg "Profile picture")

## Junior Frontend Developer

USA, VA, Franklin

+1(434)569-0425

evgeniiashirshikova@gmail.com

### About me:

I started my path as a frontend developer at 2022 when I left my banking career. I've been studying at ITgirls school as frontend developer. About a year ago I've known Webflow so I switched to webflow developing and currently I work as webflow developer on Upwork freelance. My clients are mainly web agencies and I develop websites according to their Figma designs. I often use basic JavaScript code and different JS libraries at my projects such as GSAP, Lenis etc.
My goal is to improve my JavaScript knowledge and find a job as Junior frontend developer.

### Technologies and tools

Html, CSS, SASS, GSAP, Lenis, JavaScript (basic), React (basic), Git, Webflow, Figma, Chat GPT

### Code example:

This function shows real time in different time zones eg New York and Paris:

```
function showTime(city, timeZone) {
let now = new Date();
let time = now.toLocaleTimeString("en-US", {
timeZone: timeZone,
hour: "2-digit",
minute: "2-digit",
hour12: true,
});
let hours = time.slice(0, 2);
let minutes = time.slice(3, 8);
let classHours = ".hours-" + city;
let classMinutes = ".minutes-" + city;
let hoursWrappers = document.querySelectorAll(classHours);
let minutesWrappers = document.querySelectorAll(classMinutes);
hoursWrappers.forEach((item) => {
item.innerHTML = hours;
});
minutesWrappers.forEach((item) => {
item.innerHTML = minutes;
});
setTimeout(() => showTime(city, timeZone), 1000);
}

showTime("newyork", "America/New_York");
showTime("paris", "Europe/Paris");
```

### Projects

https://github.com/EvgeniiaShirshikova/DestinyMatrix
