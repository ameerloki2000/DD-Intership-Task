# DD-Intership-Task
-First I have created a repoistory in my github 


<img width="1358" height="897" alt="image" src="https://github.com/user-attachments/assets/706f243d-980b-499e-aa4d-67a79f7eea05" />


-After that I have connected the local files with bash and pushed codes to github repo.

<img width="1095" height="277" alt="Screenshot 2026-02-24 073017 2" src="https://github.com/user-attachments/assets/6bfcabe6-b8a5-437c-bafc-043fbd6dbad5" />


-Created Dockerfiles for frontend and backend 

<img width="772" height="277" alt="image" src="https://github.com/user-attachments/assets/166fa05a-a997-48e8-a001-8d67a3ff50a8" />

<img width="807" height="411" alt="image" src="https://github.com/user-attachments/assets/18b4791b-3a0a-4e13-81bc-7e3c73ec9a6a" />




-Then created docker-compose.yml file using Mongo DB image and Nginx image


<img width="741" height="743" alt="image" src="https://github.com/user-attachments/assets/7d2e3a65-55db-4da3-8014-a5ec282102ff" />


- Launched a EC2 instance (ubuntu)

<img width="1227" height="797" alt="Screenshot 2026-02-24 143200 (ubuntu image)" src="https://github.com/user-attachments/assets/b63cd0b4-e02e-4d3b-a17d-557d4d78b66b" />



-Before CI,CD checking if it is working


-Some error has occured , So I have change db.config.js Because it was for localhost 

<img width="805" height="282" alt="image" src="https://github.com/user-attachments/assets/222e5e3e-3f08-4f37-84f7-001c4c906775" />



-Re-run docker compose


<img width="1162" height="782" alt="Screenshot 2026-02-24 150319 docker compose build" src="https://github.com/user-attachments/assets/f2ef499b-ace2-40f0-a2ac-1c19026fc28b" />



-By adding Port 80 in security groups, Docker compose worked 


<img width="1578" height="826" alt="Screenshot 2026-02-24 150922 compose successful" src="https://github.com/user-attachments/assets/3bbe2c5c-3102-426a-9bde-632d6e5ed032" />
<img width="1301" height="733" alt="Screenshot 2026-02-24 151118 add compose" src="https://github.com/user-attachments/assets/a8a2fb68-086b-4c9c-9266-1693d01d6b01" />


-Created a deploy.yml in .github/workflowa, and add Docker hub token, Github secrets (Ip and pem details)

<img width="1202" height="737" alt="Screenshot 2026-02-24 165350 dockerhub token" src="https://github.com/user-attachments/assets/08088a06-a2a0-47d8-9607-02e8023fd2b5" />

<img width="1557" height="706" alt="Screenshot 2026-02-24 165936 adding secrets" src="https://github.com/user-attachments/assets/51ad624a-f7d2-42f3-8314-8d269bfbd21b" />




-yml is pushed to github
<img width="965" height="562" alt="Screenshot 2026-02-24 173812 cicd push" src="https://github.com/user-attachments/assets/b1ab3d63-c5d5-4dd2-80e5-48efbe6d9bf2" />



-Then CI,CD pipeline triggered 

<img width="1783" height="772" alt="Screenshot 2026-02-24 174232 deploy " src="https://github.com/user-attachments/assets/f18056bd-b366-4c09-84ba-af8ef501bbea" />


<img width="1857" height="887" alt="Screenshot 2026-02-24 175117 pipeline build" src="https://github.com/user-attachments/assets/a2166eee-2787-4912-b216-33a43f9d83f4" />


<img width="1847" height="868" alt="Screenshot 2026-02-24 175230 error" src="https://github.com/user-attachments/assets/8dfc4ed2-a8e7-4cad-b154-fb963e204c4b" />

<img width="1726" height="823" alt="Screenshot 2026-02-24 181608 working" src="https://github.com/user-attachments/assets/ad5e82a1-d5b2-4460-bc4b-17f5e01ec730" />

-Finally, pipeline worked.



















