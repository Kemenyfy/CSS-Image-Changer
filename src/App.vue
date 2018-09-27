<template>
  <div class="categoriesContainer">
    <ul class="list">
            <li>
              <div class="text">
                <h2>Programming Languages</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Front-End Techs</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Back-End Techs</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Books</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Design</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Browsers</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Hosting</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Coding Classes</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>News</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Podcasts</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Collaboration</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
            <li>
              <div class="text">
                <h2>Meetups</h2>
                <p>Lorem Ipsum is a type of character crazy amount of text don't understand nothing</p>
              </div>
            </li>
        </ul>
  </div>
</template>

<script>

</script>

<style>

.content {
  position: relative;
}

.list {
  position: relative;
  top: 0;
  left: 0;
  width: 100vh;
  /* width: 100%; */
  height: 60vh;
  /* height: 100%; */
  /* background: #ccc; */
  /* padding-left: 0; */
  margin: 1em;
  /* margin-left: 1em; */
  padding: 0;
}

.list li {
  list-style: none;
  position: relative;
  width: 8.33%;
  height: 100%;
  /* border-right: 1px solid #000; */
  float: left;
  box-sizing: border-box;
  transition: 0.5s;
  text-align: center;
  overflow: hidden;
}

.list li:nth-child(1) {
  background: url(./assets/ProgrammingLanguages.jpg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(2) {
  background: url(https://picsum.photos/1000/600?image=1061);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(3) {
  background: url(https://picsum.photos/1000/600?image=1062);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(4) {
  background: url(./assets/Books.jpg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(5) {
  background: url(./assets/Design.jpg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(6) {
  background: url(./assets/Browsers.png);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(7) {
  background: url(./assets/Hosting.jpeg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(8) {
  background: url(./assets/Schools.jpg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(9) {
  background: url(./assets/News.jpeg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(10) {
  background: url(./assets/Podcasts.jpeg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(11) {
  background: url(./assets/Collaboration.jpeg);
  background-size: cover;
  background-position: left;
}

.list li:nth-child(12) {
  background: url(./assets/Meetups.png);
  background-size: cover;
  background-position: left;
}

.list:hover li {
    width: 3%;
  }

.list li:hover {
  width: 67%;
}


.list li .text {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.8);
  box-sizing: border-box;
  color: #fff;
  opacity: 0;
}

.list li:hover .text {
  transition: 0.5s;
  transition-delay: 0.5s;
  opacity: 1;
}

</style>