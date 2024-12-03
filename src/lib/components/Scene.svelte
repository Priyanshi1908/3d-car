<script>
  import { T } from '@threlte/core';
  import * as THREE from 'three';
  import { OrbitControls, Environment, Sky } from '@threlte/extras';
  import Car from '../models/free_ai_based_conceptcar_050_public_domain_cc0.svelte';
  import Apple from '../models/red_apple.svelte';

</script>

<T.PerspectiveCamera makeDefault position={[10, 10, 10]} fov={80} near={0.1} far={1000}>
<OrbitControls
     autoRotate
     autoRotateSpeed={1.0}
     allowPan={false}
     enableDamping
     maxDistance={200}
     minDistance={10}
  />
</T.PerspectiveCamera>

<Sky />



<Environment path="/hdr/" format="hdr" isBackground={false} files="metro_noord_4k.hdr" />

<T.Group position={[0, 2, 0]} scale={5}>
  <Car />
</T.Group>


<T.Group position={[0, 6.9, 1]} scale={30}>
  <Apple />
</T.Group>
