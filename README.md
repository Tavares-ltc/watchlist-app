# Watchlist 
Watchlist app is the best app to quickly organize the movies you want to see, just give two clicks any movie and that's it, will be on your Watchlist! 

![addingToWatchlist](https://user-images.githubusercontent.com/98609823/222193355-0948a0f1-be4a-4562-b10e-dd8257cd4996.gif)  
 

\
\
As you add more movies, your watchlist will become the main page of the site. Less time looking for something to watch, more time watching.

![watchlist](https://user-images.githubusercontent.com/98609823/222194700-f70a25be-ae75-417b-ab77-a218fec5a7e9.gif)


\
\
Easily mark a movie as watched just by giving a 1-5 star review.

![review](https://user-images.githubusercontent.com/98609823/222195009-3b4ce5f2-a26e-43f5-a529-3986a5e09400.gif)


\
\
Adaptative design!

https://user-images.githubusercontent.com/98609823/222196141-47227d79-6e62-4800-b1cd-f0b8fbfae822.mp4


\
\
Watchlist App.  

[watchlist-app.webm](https://user-images.githubusercontent.com/98609823/222224637-f9d6b959-0a0a-4ea1-b2ef-e3f58769643e.webm)

## Technologies
The following tools and frameworks were used in the construction of this application:
### * Front-End
<p>
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white" />
   <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
   <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
</p>

### * Back-end
<p>
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
   <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" />
   <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/TMDB-API-<blue>?style=for-the-badge" />
    <img src="https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white" />

</p>

## How to run

1. Clone this repository

```
git clone --recursive https://github.com/Tavares-ltc/watchlist-app
```

2. Create .env like the .env.example file (make sure to do that on back-end and on the front-end)

 - A TMDB Api key will be required on .env from back-end. Follow their documentation to get one, it's simple! https://developers.themoviedb.org/3/getting-started/introduction
    
3. With docker run (Don't want to use Docker? No problem, check the repositories individually and follow the documentation.)

```bash
docker-compose up --build
```

4. Run the seed coommand on the docker to make the star review work.

 ```bash
docker exec app_node npm run seed
```

5. Thats it, just navigate to http://localhost:5000
