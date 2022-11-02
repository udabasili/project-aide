
# Project note

Project Aide is a Project Management App for web developers

## Pages

- Dashboard <https://workload.dexignlab.com/xhtml/index.html>
- Clients <https://workload.dexignlab.com/xhtml/clients.html>
  - Add Client by Clicking the button <https://smarthr.dreamguystech.com/template/clients.html>
- Employees <https://smarthr.dreamguystech.com/template/employees.html>
  - Add Employees by Clicking the button <https://smarthr.dreamguystech.com/template/employees.html>
- Projects Details <https://workload.dexignlab.com/xhtml/project-details.html>
  - Add Project by Clicking the button <https://smarthr.dreamguystech.com/template/projects.html>
- Messages <https://workload.dexignlab.com/xhtml/message.html>
- My Wall <https://workload.dexignlab.com/xhtml/latest-activity.html>
- Login <https://workload.dexignlab.com/xhtml/page-login.html>
- Register <https://workload.dexignlab.com/xhtml/page-register.html>

## Technology

- Next.js
- MongoDB
- firebase authentication
Craco is used here to access the webpack and set the path to work with the tsconfig path json
so that we can use @/components in our projects we also have to set the set the postgress and tailwindcss to work there

Username: james@yahoo.com johnfiswa@gmail.com
password: 1234567

## To deploy

<https://medium.com/developer-rants/deploying-typescript-node-js-applications-to-heroku-81dd75424ce0>

- go to client and run yarn run build
- grab build content into a folder in server called public which we create if it is not there
- go to server folder and run
  - git add .
  - git commit -m ''
  - git push heroku master
