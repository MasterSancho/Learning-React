-> npx create-react-app frontend

-> cd frontend

-> change-> title && description

-> clean folder-> DELETE-> (setupTests.js && logo.svg && App.test.js && App.css)

-> {rm -rf.git} -> in terminal to move GIT to root folder
+ {.gitignore} move to root folder
+ in .gitignore edit -> #dependencies (node_modules node_modules/)
+ #misc after (.DS_Store) add (.env)

-> in src folder -> create (components folder) && {Footer.js} && {Header.js}
+ && bring them to {App.js}

-> Bootswatch download theme && bring it to src folder
+ (import to index.js {import './bootstrap.min.css})
+ open second terminal -> write (cd frontend) && (npm i react-bootstrap)

-> in App.js (import { Container } from 'react-bootstrap')
+ bring <Container> to main tag

-> footer Copyright &copy; ProShop
+ css main { min-height: 80vh }

-> bring Navbar code from (react-bootstrap.github.io/components/navbar) after that
+ import { Navbar, Nav, Container } from 'react-bootstrap'

-> bring font-awesome link from cdnjs.com to index.html -> head
+ bring icons to Header.js
+ <i className='fas fa-shooping-cart'></i>
+ <i className='fas fa-user'></i>

-> css in App.js -> main tag add className='py-3'