# My Morning News Part 5 Backend
![Express JS Logo](https://nick-rodriguez.info/media/ExpressJs.png)

La Capsule #lacapsule

MorningNews est une application qui va vous permettre d’afficher les news récentes du journal Tech Crunch. Vous pourrez également sauvegarder vos articles préférés et les retrouver en vous connectant à votre compte.

Cette application sera développée en React mais cette fois-ci, vous allez lui ajouter de nouvelles briques techniques (navigation, Redux, authentification…).

Aujourd’hui, vous allez améliorer l’usage de votre application en rendant votre store persistant. Cela signifie que l’utilisateur pourra rester connecté et conserver ses articles favoris même lorsqu’il rafraîchit la page. Vous ajouterez également une fonctionnalité vous permettant de masquer certains articles, ceux que vous avez déjà lus par exemple.

## installation

### Créer Express projet
genere le structure backend
`express --no-view --git ./`

### Installation 
1. yarn install
`yarn install`
2. dotenv
`yarn add dotenv`
3. mongoose
`yarn add mongoose`
4. node-fetch
`yarn add node-fetch@2`
5. uid2
`yarn add uid2`
5. bcrypt
`yarn add bcrypt`
6. cors
`yarn add cors`
cors: est le gatekeeper pour le backend
un securitie
    - ajouter cors a ligne 10
```
const cors = require('cors');
app.use(cors());
```


