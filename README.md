# Card-building
html and css only

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>card designing</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,300&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Poppins:ital,wght@1,300&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&family=Playfair+Display&family=Poppins:ital,wght@1,300&display=swap"
      rel="stylesheet"
    />
  </head>
  <style>
    * {
      margin: 0px;
      padding: 0px;
    }
    body {
      background-color: grey;
      padding: 45px;
      display: flex;
    }
    .card {
      background-color: white;
      width: 261px;
      /* height: 450px; */
      border-radius: 7px;
      padding: 0 0 30px 0;
      margin: 4px;
    }

    .image {
      padding: 5px;
    }
    .image img {
      border-radius: 7px;
    }
    .content {
      padding: 7px 13px;
      font-family: "Poppins", sans-serif;
    }

    .content h2 {
      font-family: "Oswald", sans-serif;
      color: rgba(0, 0, 0, 0.811);
    }

    .content p {
      font-size: 13px;
      color: grey;
    }
    .capsules {
      padding: 0px 28px 0px 14px;
    }
    .capsules span {
      border: 1px solid grey;
      padding: 0px 6px;
      border-radius: 7px;
      font-size: 12px;
      font-family: "Playfair Display", serif;
    }
    .button {
      text-align: center;
      /* margin-top: auto; */
    }
    .button button {
      padding: 7px 20px;
      border-radius: 15px;
      background-color: rgb(157, 184, 201);
      color: rgba(0, 0, 255, 0.566);
      font-size: 12px;
      border: none;
      margin-top: 7px;
      font-weight: bold;
      cursor: pointer;
    }
    .button button:hover {
      background-color: rgb(188, 223, 235);
      color: rgba(218, 26, 42, 0.566);
    }
  </style>
  <body>
    <!-- Card.png  is a file which contains a card image. write html and css to design this card -->
    <div class="card">
      <div class="image">
        <img
          width="250"
          src="https://upload.wikimedia.org/wikipedia/commons/8/80/A_boat_man_with_his_small_boat.jpg"
          alt=""
        />
      </div>
      <div class="capsules">
        <span>Nature</span>
        <span>Lake</span>
      </div>
      <div class="content">
        <h2>Nature</h2>
        <p>
          Birds in flight, above the lake, Their wings outstretched, no burdens
          take. Soaring high, with freedom's grace, In nature's realm, they find
          their place.
        </p>
      </div>
      <div class="button">
        <button>Read More</button>
      </div>
    </div>

    <!-- 2 -->

    <div class="card">
      <div class="image">
        <img
          width="250"
          src="https://images.pexels.com/photos/4910956/pexels-photo-4910956.jpeg?auto=compress&cs=tinysrgb&w=600"
          alt=""
        />
      </div>
      <div class="capsules">
        <span>Journey</span>
        <span>Couple</span>
      </div>
      <div class="content">
        <h2>Journey</h2>
        <p>
          On foot we tread, through forests dense, Where sunlight filters,
          through the branches tense. A symphony of sounds, the trees impart, In
          nature's embrace, we find our start.
        </p>
      </div>
      <div class="button">
        <button>Read More</button>
      </div>
    </div>
    <!-- 3 -->

    <div class="card">
      <div class="image">
        <img
          width="250"
          src="https://images.pexels.com/photos/4056535/pexels-photo-4056535.jpeg?auto=compress&cs=tinysrgb&w=600"
          alt=""
        />
      </div>
      <div class="capsules">
        <span>Meditation</span>
        <span>Posture</span>
      </div>
      <div class="content">
        <h2>Meditation</h2>
        <p>
          Amidst the trees, where sunlight streams, Meditation's embrace, in
          nature's dreams. The rustling leaves, a gentle song, As inner harmony,
          becomes so strong.
        </p>
      </div>
      <div class="button">
        <button>Read More</button>
      </div>
    </div>
    <!--  -->

    <div class="card">
      <div class="image">
        <img
          width="250"
          src="https://images.pexels.com/photos/3077837/pexels-photo-3077837.jpeg?auto=compress&cs=tinysrgb&w=600"
          alt=""
        />
      </div>
      <div class="capsules">
        <span>Forest</span>
        <span>Leafs</span>
      </div>
      <div class="content">
        <h2>Forest</h2>
        <p>
          Through sun-dappled glades, where wildflowers bloom, A symphony of
          nature, in gentle tune. Butterflies flutter, with colors bright, As
          sunlight dances, through leaves so light.
        </p>
      </div>
      <div class="button">
        <button>Read More</button>
      </div>
    </div>
    <!--  -->

    <div class="card">
      <div class="image">
        <img
          width="250"
          src="https://images.pexels.com/photos/7938050/pexels-photo-7938050.jpeg?auto=compress&cs=tinysrgb&w=600"
          alt=""
        />
      </div>
      <div class="capsules">
        <span>Family</span>
        <span>Love</span>
      </div>
      <div class="content">
        <h2>Family</h2>
        <p>
          Exploring new horizons, we journey so far, Family's compass, guiding
          our star. Through landscapes vast, and cultures diverse, Together we
          wander, our spirits immerse.
        </p>
      </div>

      <div class="button">
        <button>Read More</button>
      </div>
    </div>
  </body>
</html>
