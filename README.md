FootRaters

This application is made for soccer fans who wish to create a page about a team that they love and write their statistics. Alongside with that they can also add players and mention their life story and what got them there. The use of images makes the visual great and a forms a good user experience. It was built throught a react app with lots of html,css,usestates and CRUD. In order to run this project, you will have to run both my react files and springboot for the back-end and front-end to work togheter. I faced a big challenge with trying to perfectionnate the CSS. I also had many and many elements on my App.js which was really hard to keep up at some points. My CRUD also gave me a headache because I would know what to give the requests but it would always somehow fail. I passed hours and hours on inspect mode. For features I would love to add player statistics and also team formation with the current players.

I have 3 entities: Team,statistic,Player
Each team had statistics and each player had a team.

: Entity-Relationship Diagram
![image](https://user-images.githubusercontent.com/92550620/209455932-f5c1a1dc-037b-4d8e-a229-ad6a52d8e2dd.png)

End-points:

/api/teams/{team_id}/players POST players
/api/teams/{team_id}/players GET players
/api/teams/{team_id}/players DELETE players
/api/teams Post teams
/api/teams/id PUT teams
/api/teams/id DELETE teams

/api/players/{player_id} GET player
/api/players/{player_id} update player
/api/players/{player_id} delete player

![image](https://user-images.githubusercontent.com/92550620/209456019-21308281-edc7-46d9-a785-78c645a14d6a.png)
![image](https://user-images.githubusercontent.com/92550620/209456026-faac89c7-b2a5-4579-8f2b-371e2f9d47a8.png)
 Users can add a team, view the team, add players to that team, edit the information for that team, and delete that team.
 The page colors depend on user input in the forms which is a nice feature.
 The nav slides down and shows players all the teams they added so they can click and view other teams 
