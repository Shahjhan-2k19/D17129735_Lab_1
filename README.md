# Rich_web_Applications
web extention shows love for red merc car on web page 
i wanted to make text large but it was not showing pictures and text together.
//All p elements will be extra large.
const p = document.getElementsByTagName("p");
for (let i = 0; i < p.length; i++){
    p[i].style.fontSize = "x-large";
}
