Ajouter le SDK Firebase


Ensuite, initialisez Firebase et commencez à exploiter les SDK pour les produits que vous souhaitez utiliser.

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
const firebaseConfig = {
  apiKey: "AIzaSyCX2VtIXQwQ4aS7HJIVvHtxktZcZuCpq8o",
  authDomain: "rezay-bar.firebaseapp.com",
  databaseURL: "https://rezay-bar-default-rtdb.europe-west1.firebasedatabase.app",
  projectId: "rezay-bar",
  storageBucket: "rezay-bar.appspot.com",
  messagingSenderId: "628198380812",
  appId: "1:628198380812:web:e5a47da779b43fad4be529"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);