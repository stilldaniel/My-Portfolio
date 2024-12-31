<template>
  <div class="wrapper">
    <div class="main-container">
    <div class="container-one">
        <div class="profile">
            <img src="../assets/Daniel.jpg" alt="">
            <h3>Ogundipe Daniel</h3>
            <p>Sofware Developer</p>
        </div>
        <div class="social-links">
            <div class="link">
                <a href="https://github.com/stilldaniel" target="_blank">
                    <i class="fa-brands fa-github"></i>
                    <h2>GitHub</h2>
                </a>
            </div>
            <div class="link">
                <a href="https://www.linkedin.com/in/daniel-ogundipe-ab620a318" target="_blank">
                    <i class="fa-brands fa-linkedin"></i>
                    <h2>LinkedIn</h2>
                </a>
            </div>
            <div class="link">
                <a href="https://x.com/_stilldaniel" target="_blank">
                    <i class="fa-brands fa-twitter"></i>
                    <h2>Twitter</h2>
                </a>
            </div>
            <div class="link">
                <a href="https://www.instagram.com/_stilldaniel/" target="_blank">
                    <i class="fa-brands fa-instagram"></i>
                    <h2>Instagram</h2>
                </a>
            </div>
        </div>
    </div>
    <div class="container-two">
        <div class="about-me">
            <h1>About Me</h1>
            <p>
                As a Frontend Developer, I’ve spent years honing my skills in HTML, CSS, TypeScript, JavaScript, and frameworks like React, Vue.js, and Next.Js. I love the challenge of taking a design and bringing it to life in a way that’s not just visually appealing, but also works seamlessly across all devices. My work is all about creating responsive, user-friendly web applications that people enjoy using. I’m always up for solving tricky problems—whether it’s optimizing performance or making sure everything runs smoothly. I’m a big believer in writing clean, maintainable code and I’m constantly learning to stay ahead of the curve. Collaboration is key for me, and I enjoy working closely with designers, backend developers, and stakeholders to create digital experiences that really make an impact.    
            </p>
        </div>
        <div class="technology-section">
            <h1>Technologies Studied</h1>
            <div class="logos">
                <i class="fa-brands fa-js"></i>
                <i class="fa-brands fa-react"></i>
                <i class="fa-brands fa-vuejs"></i>
            </div>
        </div>
        <div class="button-container">
            <div class="projects-button">
                <a href="https://github.com/stilldaniel" target="_blank">My Projects</a>
            </div>
            <div class="projects-button">
                <a href="/Inioluwa.pdf" target="_blank" rel="noopener noreferrer">My Resume</a>
            </div>
        </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            
        } 
    } 
}
</script>

<style scoped>
.wrapper {
    display: flex;
    justify-content: center;
} 
img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 55% 45% 55% 45%;
    overflow: hidden;
    animation: imgFloat 7s ease-in-out infinite;
}
@keyframes imgFloat {
    50% {
        transform: translateY(10px);
        border-radius: 45% 55% 45% 55%;
    }
} 
.main-container {
    display: flex;
    flex-direction: row;
    border-radius: 25px;
    background-color: #cecece;
    width: 60%;
    background-color: #a0d4ff;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
.container-one {
    background-color: #1292ee;
    padding: 2.5%;
    width: 30%;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
.container-two {
    margin: 2.5%;
    width: 70%;
}
.link a {
    text-decoration: none;
    color: #2c3e50;
    font-size: 12px;
} 
.link i {
    font-size: 25px;
}
.about-me {
    text-align: left;
}
.logos {
    display: flex;
    justify-content: center;
    gap: 20px;
} 
.logos i {
    font-size: 2.5rem;
}
.projects-button {
    background-color: #005caa;
    margin: 5px;
    padding: 8px;
    border-radius: 15px;
} 
.projects-button a {
    text-decoration: none;
    color: #fff;
}
.button-container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 10px;
    margin-top: 5%;
}
@media only screen and (max-width: 1024px) {
    img {
        width: 180px;
        height: 180px;
    } 
} 
@media only screen and (max-width: 950px) {
    .main-container {
        width: 95%;
    } 
}
@media only screen and (max-width: 700px) {
    img {
        width: 150px;
        height: 150px;
    } 
}
@media only screen and (max-width: 580px) {
    .technology-section h1 {
        font-size: 1.5rem;
    }
}
@media only screen and (max-width: 530px) {
    .about-me p {
        font-size: 0.9rem;
    } 
    .technology-section h1 {
        font-size: 1.4rem;
    }
    img {
        width: 100px;
        height: 100px;
    }
} 
@media only screen and (max-width: 420px) {
    .link a {
        font-size: 10px;
    } 
    .link i {
        font-size: 22px;
    }
    .technology-section h1 {
        font-size: 1.2rem;
    }
    .projects-button a {
        font-size: 0.8rem;
    }
    .logos i {
        font-size: 2rem;
    }
    .about-me p {
        font-size: 0.8rem;
    }
}
@media only screen and (max-width: 360px) {
    img {
        width: 70px;
        height: 70px;
    }
    .about-me p {
        font-size: 0.6rem;
    }
    .technology-section h1 {
        font-size: 1rem;
    }
    .logos i {
        font-size: 1.5rem;
    }
    .projects-button {
        margin: 3px;
        padding: 5px;
    }
    .projects-button a {
        font-size: 0.6rem;
    }
    .link a {
        font-size: 5px;
    } 
    .link i {
        font-size: 15px;
    }
}
</style>
