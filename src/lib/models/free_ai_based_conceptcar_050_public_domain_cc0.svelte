<!--
Auto-generated by: https://github.com/threlte/threlte/tree/main/packages/gltf
Command: npx @threlte/gltf@2.0.3 free_ai_based_conceptcar_050_public_domain_cc0.glb
Author: Unity Fan youtube channel (https://sketchfab.com/unityfan777)
License: SKETCHFAB Standard (https://sketchfab.com/licenses)
Source: https://sketchfab.com/3d-models/free-ai-based-conceptcar-050-public-domain-cc0-3f7a98a53efe48068adddf0c0f3ddbae
Title: FREE Ai based ConceptCar 050 public domain (CC0)
-->

<script>
  import { Group } from 'three'
  import { T, forwardEventHandlers } from '@threlte/core'
  import { useGltf } from '@threlte/extras'

  export const ref = new Group()

  const gltf = useGltf('3dModels/GLB/free_ai_based_conceptcar_050_public_domain_cc0.glb')

  const component = forwardEventHandlers()
</script>

<T is={ref} dispose={false} {...$$restProps} bind:this={$component}>
  {#await gltf}
    <slot name="fallback" />
  {:then gltf}
    <T.Group scale={0.01}>
      <T.Group rotation={[-Math.PI / 2, 0, 0]} scale={100}>
        <T.Mesh geometry={gltf.nodes.Cube042_plastic_smooth_0.geometry} material={gltf.materials.plastic_smooth} />
        <T.Mesh geometry={gltf.nodes.Cube042_grill001_0.geometry} material={gltf.materials['grill.001']} />
      </T.Group>
      <T.Group position={[102.47, 38.24, 130]} rotation={[-Math.PI / 2, 0, Math.PI]} scale={102.43}>
        <T.Mesh geometry={gltf.nodes.rim_235001_rims_0.geometry} material={gltf.materials.rims} />
        <T.Mesh geometry={gltf.nodes.rim_235001_chrome_0.geometry} material={gltf.materials.chrome} />
      </T.Group>
      <T.Group position={[102.47, 38.24, 130]} rotation={[-Math.PI / 2, 0, -Math.PI]} scale={127.37}>
        <T.Mesh geometry={gltf.nodes.tire_001_R17001_rubber_tires_0.geometry} material={gltf.materials.rubber_tires} />
        <T.Mesh
          geometry={gltf.nodes.tire_001_R17001_tire_protector_0.geometry}
          material={gltf.materials.tire_protector}
        />
      </T.Group>
      <T.Group position={[102.47, 38.24, -158.29]} rotation={[-Math.PI / 2, 0, Math.PI]} scale={102.43}>
        <T.Mesh geometry={gltf.nodes.rim_235002_rims_0.geometry} material={gltf.materials.rims} />
        <T.Mesh geometry={gltf.nodes.rim_235002_chrome_0.geometry} material={gltf.materials.chrome} />
      </T.Group>
      <T.Group position={[102.47, 38.24, -158.29]} rotation={[-Math.PI / 2, 0, -Math.PI]} scale={127.37}>
        <T.Mesh geometry={gltf.nodes.tire_001_R17002_rubber_tires_0.geometry} material={gltf.materials.rubber_tires} />
        <T.Mesh
          geometry={gltf.nodes.tire_001_R17002_tire_protector_0.geometry}
          material={gltf.materials.tire_protector}
        />
      </T.Group>
      <T.Group position={[-102.4, 38.24, 130]} rotation={[-Math.PI / 2, 0, Math.PI]} scale={100}>
        <T.Mesh geometry={gltf.nodes.rim_235003_rims_0.geometry} material={gltf.materials.rims} />
        <T.Mesh geometry={gltf.nodes.rim_235003_chrome_0.geometry} material={gltf.materials.chrome} />
      </T.Group>
      <T.Group position={[-102.45, 38.24, 130]} rotation={[-Math.PI / 2, 0, -Math.PI]} scale={127.37}>
        <T.Mesh geometry={gltf.nodes.tire_001_R17003_rubber_tires_0.geometry} material={gltf.materials.rubber_tires} />
        <T.Mesh
          geometry={gltf.nodes.tire_001_R17003_tire_protector_0.geometry}
          material={gltf.materials.tire_protector}
        />
      </T.Group>
      <T.Group position={[-102.45, 38.24, -158.29]} rotation={[-Math.PI / 2, 0, -Math.PI]} scale={127.37}>
        <T.Mesh geometry={gltf.nodes.tire_001_R17004_rubber_tires_0.geometry} material={gltf.materials.rubber_tires} />
        <T.Mesh
          geometry={gltf.nodes.tire_001_R17004_tire_protector_0.geometry}
          material={gltf.materials.tire_protector}
        />
      </T.Group>
      <T.Group position={[-102.4, 38.24, -158.29]} rotation={[-Math.PI / 2, 0, Math.PI]} scale={100}>
        <T.Mesh geometry={gltf.nodes.rim_235004_rims_0.geometry} material={gltf.materials.rims} />
        <T.Mesh geometry={gltf.nodes.rim_235004_chrome_0.geometry} material={gltf.materials.chrome} />
      </T.Group>
      <T.Mesh
        geometry={gltf.nodes.Cube_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube001_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube002_glass_0.geometry}
        material={gltf.materials.glass}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube003_glass_0.geometry}
        material={gltf.materials.glass}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube004_grill_0.geometry}
        material={gltf.materials.grill}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube005_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube006_body_0.geometry}
        material={gltf.materials.body}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube007_body_0.geometry}
        material={gltf.materials.body}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube008_body_0.geometry}
        material={gltf.materials.body}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube009_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube010_body_0.geometry}
        material={gltf.materials.body}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube011_body_0.geometry}
        material={gltf.materials.body}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube012_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube013_lights_0.geometry}
        material={gltf.materials.lights}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube014_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube015_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube016_taillights_0.geometry}
        material={gltf.materials.taillights}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube017_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube018_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube019_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube020_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube021_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube022_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube023_grill_0.geometry}
        material={gltf.materials.grill}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube024_blocker_0.geometry}
        material={gltf.materials.blocker}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube025_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube026_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube027_grill001_0.geometry}
        material={gltf.materials['grill.001']}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube028_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube029_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube033_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube034_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube035_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube036_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube037_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube038_red_deco_0.geometry}
        material={gltf.materials.red_deco}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube039_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube040_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube041_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube043_grill_0.geometry}
        material={gltf.materials.grill}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube044_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube045_grill_0.geometry}
        material={gltf.materials.grill}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube046_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube047_blocker_0.geometry}
        material={gltf.materials.blocker}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.Cube048_plastic_smooth_0.geometry}
        material={gltf.materials.plastic_smooth}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={100}
      />
      <T.Mesh
        geometry={gltf.nodes.shadow_shadow_0.geometry}
        material={gltf.materials.shadow}
        rotation={[-Math.PI / 2, 0, 0]}
        scale={440.23}
      />
    </T.Group>
  {:catch error}
    <slot name="error" {error} />
  {/await}

  <slot {ref} />
</T>
