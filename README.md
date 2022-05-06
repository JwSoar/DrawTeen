# DrawTeen

Please go to the Release (Drawteen v1.0) on the right side of the projet to download all files. (The code and settings)
Or go to this link: https://github.com/JwSoar/DrawTeen/releases/tag/drawteengame

Drawing and guessing game

Unity Version - 2021.2.15f1

VS Version 2019

This is multiplayer network game with WebGL

Game developed by: Jianchi Wei, Yannong Li, Zhiyu Wan, and Jiajun Zhu

How to play the game:
  As server end (only working in Windows systgem):
  1. Download all files, including 'drawteen-1.rar' and 'Drawteengame.Server.rar'.
  2. To extract them.
  3. After extracting the server files, open "MyGame.Server.sln" with Visual Studio Version - 2019, and run.
  4. Importing the drawteen-1 to you unity project with Unity Version - 2021.2.15f1 (open Unity Hub, and click 'New Project')
  5. HP Server End: 9000, default server IP should be your IPv4 address: localhost: 9000.
  6. Go to 'connect.cs', on the line 20 (on the script file, you can modity after importing the project), change the "localhost" to your IPv4 address (such as 172.1..).
  7. On the Unity Project, click 'File' and choose 'Build and Run' with WebGL.
 
 Client or other players can connect to the server by server IP
 
Testing suggestion:
 You can open four browser windows by coping the same IP address to test if the game working with four players. (Google Chrome should be better)

The code that we did not write:
Code from GitHub:
UnityWebsocket: psygames/UnityWebSocket: https://github.com/psygames/UnityWebSocket

project from Unity Store:
Free Draw: https://assetstore.unity.com/packages/tools/painting/free-draw-simple-drawing-on-sprites-2d-textures-113131
