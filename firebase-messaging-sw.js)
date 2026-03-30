// firebase-messaging-sw.js
importScripts('https://www.gstatic.com/firebasejs/10.8.0/firebase-app-compat.js');
importScripts('https://www.gstatic.com/firebasejs/10.8.0/firebase-messaging-compat.js');

firebase.initializeApp({
    apiKey: "AIzaSyDLXIdiehtoCfRKH9qQYU2u5IoRDk7KmxM",
    authDomain: "quanlykhachhangvar.firebaseapp.com",
    projectId: "quanlykhachhangvar",
    messagingSenderId: "445137801788",
    appId: "1:445137801788:web:a5007ec21d3c8671eba939"
});

const messaging = firebase.messaging();

messaging.onBackgroundMessage((payload) => {
    const notificationTitle = payload.notification.title;
    const notificationOptions = {
        body: payload.notification.body,
        icon: 'https://cameradalat.com/wp-content/uploads/2026/02/VarSport-Logo-scaled.png'
    };
    self.registration.showNotification(notificationTitle, notificationOptions);
});