
Dalani Studio

#### By 
Muriithi Joyce
## Description
This is a landing page for a fictional studio that has different sections, welcome , about us services ,what we do, portfolio and contact us.
#### Setup/Installation Requirements
To view the website, go to 

### Live Link



## Technologies Used
HTML
Bootstrap
JS
 JQuery 
  CSS

## Support and contact details
incase of any question,concern or idea please feel free to contact me at rachelmuriithi57@gmail.com

### Konown Bugs
The page when on full scree the flag on the topmost part streches but on minimizing the screen it works perfectly well.
Any suggestion or idea on how to go about it is welcomed.

Licenced under the [MIT Licence](LICENCE)

/* Second Section */
.second {
    display: flex;
    justify-content: center;
    align-items: center;
}

#aboutUs {
    height: auto;
    min-height: 40vh;
    width: 100%;
    padding: 1rem;
}

#services-wrapper {
    padding: 1rem;
    position: relative;
}

#services {
    background-image: url("../assets/backgrounds/s_image.jpg");
    background-size: cover;
    background-position: center;
    height: auto;
    min-height: 40vh;
    width: 100%;
    position: absolute;
    left: 0;
}

/* What We Do */
#thirdSection {
    height: auto;
}

/* Contact Us section */
#contactUsWrapper {
    position: relative;
}

#contactUs {
    height: auto;
    padding-bottom: 2rem;
    min-width: 100%;
    position: absolute;
    left: 0;
    right: 0;
    background-image: url("../assets/backgrounds/c_image.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    color: white;
}

.form-control::-webkit-input-placeholder {
    color: white;
    font-style: italic;
    opacity: 0.7;
}

#socialMedia {
    height: auto;
    width: 100%;
}

#icons {
    height: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

#icons a {
    padding: 1rem;
}

/* Media Queries */
@media screen and (min-width:720px) {
    #header p {
        font-size: 3rem;
    }

}

.image-block {
    background-color: white;
    position: relative;
    width: 100%;
}

.img-ovly-1,
.img-ovly-2,
.img-ovly-3,
.img-ovly-4,
.img-ovly-5,
.img-ovly-6,
.img-ovly-7,
.img-ovly-8 {
    background-color: rgba(255, 255, 255, 0.85);
    position: absolute;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(20, 20, 20);
}

.pr-1,
.pr-2,
.pr-3,
.pr-4,
.pr-5,
.pr-6,
.pr-7,
.pr-8 {
    width: fit-content;
}

.desc {
    transition: 300ms linear;
}

#icons a {
    transition: 300ms;
}
#icons a:hover {
    transform: scale(1.25);
}
.project-title{
    padding-bottom: 0.5rem;
    border-bottom: 0.2rem solid black;
}