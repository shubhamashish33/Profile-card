# Profile-card
Short and Simple Profile-card

#### [Visit Now 🚀](https://shubhamashish33.github.io/Profile-card/)

## Screenshot
![chrome_odQz9U8oFg](https://user-images.githubusercontent.com/78084828/129530412-00ceaa45-34b3-42c9-8462-3c63bca1ebf6.png)

## Sample Code
### HTML
```html
<div class="card">
        <div class="content">
            <img src="./assets/img/profile-pic (6).png" alt="profile-pic">
            <h3>UI UX Designer | Web Developer</h3>
            <h2>Shubham Ashish</h2>
            <p>Hi I'm Shubham Ashish, B. Tech Computer Science Student. Have interest in designing content and coding
                related stuff.</p>
        </div>
        <div class="icons">
            <div class="twitter">
                <a href="https://twitter.com/imaashish_
                " target="_blank"><i class="bi bi-twitter"></i></a>
            </div>
            <div class="instagram">
                <a href="https://www.linkedin.com/in/shubham-ashish-81a6a01b2/
                " target="_blank"><i class="bi bi-linkedin"></i></a>
            </div>
            <div class="github">
                <a href="https://github.com/shubhamashish33
                " target="_blank">
                    <i class="bi bi-github"></i></a>
            </div>
        </div>
    </div>
```
### CSS
```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;500&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body {
  /* background-image: linear-gradient(to bottom, #FD97F7,#D42DF9); */
  background-color: #f74cee;
  background-image: linear-gradient(19deg, #f74cee 0%, #b721ff 100%);
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
h3 {
  font-weight: 100;
  margin-top: 20px;
  margin-left: 50px;
}
p {
  margin-left: 50px;
  font-weight: 300;
  margin-top: 10px;
  font-size: 12px;
}
h2 {
  margin-left: 50px;
  margin-top: 10px;
  font-weight: 500;
}

.card {
  background-color: #a132c5;
  width: 30%;
  margin: auto;
  filter: drop-shadow(2px 4px 20px #3a3a3a2c);
  border-radius: 20px;
  color: white;
}
img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 5px solid white;
  margin-left: 50px;
  margin-top: 20px;
  filter: drop-shadow(2px 4px 20px #3a3a3a2c);
}
.icons {
  display: flex;
  justify-content: space-around;
  margin-top: 30px;
  margin-bottom: 30px;
}
.twitter,.instagram,.github{
    background-color: white;
    color: black;
    width: 60px;
    height: 60px;
    text-align: center;
    padding-top: 10px;
    font-size: 28px;
    border-radius: 50%;
    cursor: pointer;
}
a{
  color: black;
}
@media screen and (max-width: 476px){
  body{
    /* display: none; */
    width: 80%;
    margin: auto;
  }
  .card{
    width: 100%;
    margin-top: 100px;
  }
  h3,h2,p,img{
    margin-left: 12px;
  }
}
```
# Follow me🌟

### [![](https://img.shields.io/twitter/follow/imaashish_?style=social)](https://twitter.com/imaashish_)