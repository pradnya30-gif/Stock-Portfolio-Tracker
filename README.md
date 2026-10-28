<!DOCTYPE html>
<html>
   <head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400&display=swap" rel="stylesheet">
    <script>
      tailwind.config = {
        theme: {
          extend: {
            fontFamily: {
              caveat: ["Caveat", "cursive"],
              breeserif: ["Bree Serif", "serif"],
              roboto: ["Roboto", "sans-serif"],
            },
          },
        },
      };
    </script>
  </head>
  <body>
    <div class="bg-[url('https://assets.ccbp.in/frontend/react-js/congrats-card-bg.png')] bg-[#f0f4f8] min-h-screen flex flex-col justify-center items-center">
      <h1 class="text-6xl text-[#102a43] mb-6">Welcome</h1>
      <div class="bg-white rounded-3xl p-6 m-4 flex flex-col justify-center items-center">
        <img
          src="https://assets.ccbp.in/frontend/react-js/congrats-card-profile-img.png"
          alt="profile"
        />
        <h2 class="text-[#334e68] text-4xl mt-6">Kiran V</h2>
        <p class="text-[#486581] text-lg text-center m-8">Vishnu Institute of Computer Education and Technology, Bhimavaram</p>
      </div>
    </div>
  </body>
</html>