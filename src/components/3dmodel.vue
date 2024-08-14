<template>
	<card>
	  <div ref="canvasContainer" class="model-container">hello</div>
	   <!-- <h1>helo</h1> -->
	</card>
  </template>

<script setup>
import card from "../components/3dcard.vue";

</script>

<!-- <script setup>
import { onMounted, ref } from "vue";
import * as THREE from "three";
import { GLTFLoader } from "three/examples/jsm/loaders/GLTFLoader";
import { OrbitControls } from "three/examples/jsm/controls/OrbitControls";
import card from "../components/3dcard.vue";
const canvasContainer = ref(null);

onMounted(() => {
  // Create a Three.JS Scene
  const scene = new THREE.Scene();

  // Create a new camera with positions and angles
  const camera = new THREE.PerspectiveCamera(
    30,
    window.innerWidth / window.innerHeight,
    0.1,
    980
  );
  camera.position.z = 5; // Set camera position

  // Add lighting to the scene
  const ambientLight = new THREE.AmbientLight(0x404090); // Soft white light
  scene.add(ambientLight);

  const directionalLight = new THREE.DirectionalLight(0xffffff, 2);
  directionalLight.position.set(3, 3, 3).normalize();
  scene.add(directionalLight);

  // Instantiate a loader for the .gltf file
  const loader = new GLTFLoader();

  // Load the file
  loader.load(
    `src/assets/submarine/scene.gltf`,
    function (gltf) {
      // If the file is loaded, add it to the scene
      const object = gltf.scene;
      scene.add(object);

      // Center the model in the scene
      const box = new THREE.Box3().setFromObject(object);
      const size = box.getSize(new THREE.Vector3()).length();
      const center = box.getCenter(new THREE.Vector3());
      object.position.sub(center);
      camera.position.z = size * 1.5; // Adjust camera distance
    },
    function (xhr) {
      // While it is loading, log the progress
      console.log((xhr.loaded / xhr.total) * 100 + "% loaded");
    },
    function (error) {
      // If there is an error, log it
      console.error(error);
    }
  );

  // Instantiate a new renderer and set its size
  const renderer = new THREE.WebGLRenderer({ alpha: true }); // Alpha: true allows for the transparent background
  renderer.setSize(380, 280);

  // Add the renderer to the DOM
  canvasContainer.value.appendChild(renderer.domElement);

  // Create OrbitControls for the camera
  const controls = new OrbitControls(camera, renderer.domElement);

  // Animation loop
  function animate() {
    requestAnimationFrame(animate);
    controls.update(); // Update controls
    renderer.render(scene, camera);
  }
  animate();

  // Handle window resize
  window.addEventListener("resize", () => {
    camera.aspect = window.innerWidth / window.innerHeight;
    camera.updateProjectionMatrix();
    renderer.setSize(window.innerWidth, window.innerHeight);
  });
});
</script>


<style>
.model-container {
  /* margin-bottom: 20px; */
  position: absolute;
  height: 280px;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 400px;
  z-index: 1;
  /* top: 20%; */
  /* left: 50%; */
  /* border: 2px solid orange; */
}
canvas {
  z-index: 1;
}
</style> -->
