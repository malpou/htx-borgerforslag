<script setup lang="ts">


// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyA4qhVo9mDIwFLPFGe_9j5X4UXjYV8-GYs",
  authDomain: "htx-borgerforslag.firebaseapp.com",
  projectId: "htx-borgerforslag",
  storageBucket: "htx-borgerforslag.appspot.com",
  messagingSenderId: "923302169514",
  appId: "1:923302169514:web:0de11032c1a5b7bafb79d3",
  measurementId: "G-4TGW969SBE"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

</script>

<template>
<h1>Test site</h1>
</template>

<style>

</style>
