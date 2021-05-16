<script>
	import { FirebaseApp } from 'sveltefire';
	import firebase from 'firebase/app';
	import 'firebase/firestore';
	import 'firebase/auth';

	const firebaseConfig = {
    apiKey: "AIzaSyAQsq59CxdKF2CmbBEQuLaIBh5qgTl1Bvw",
    authDomain: "davids-svelte-chat-app.firebaseapp.com",
    projectId: "davids-svelte-chat-app",
    storageBucket: "davids-svelte-chat-app.appspot.com",
    messagingSenderId: "886661467942",
    appId: "1:886661467942:web:2615e37ba4d57612c17be7",
    measurementId: "G-M9D3D58WY9"
  };
 

  firebase.initializeApp(firebaseConfig);
  firebase.analytics();

</script>

<main>
	
	<FirebaseApp >
		
	</FirebaseApp>
</main>

