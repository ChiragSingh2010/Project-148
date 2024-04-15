# PRO-C150-Student-Activity
<a-assets>      
      <a-assets-item id="person" src="Models/3rd_person_model/scene.gltf"></a-assets-item>
      <a-assets-item id="dog" src="Models/dog/scene.gltf"></a-assets-item>
      

    </a-assets>
    

    <a-entity scale="0.003 0.003 0.003" gltf-model="#person" position="-2 0.4 3" shadow="cast:true"></a-entity>
    <a-entity scale="0.003 0.003 0.003" gltf-model="#dog" position="0 0.4 3" shadow="cast:true"></a-entity>
    <a-entity light="type:point; castShadow:true; color:#e6ca14; intensity:2.35" position="-5 8 1"></a-entity>
    <a-entity light="type:ambient;"></a-entity>