<script>

import Avatar from '$lib/components/Avatar.svelte';

let sampleImg = 'https://ipfs.runfission.com/ipns/jeffg.files.fission.name/p/images/people.jpg';


</script>

<h1>Hello world</h1>

<div>
  <Avatar image={sampleImg} size="16"/>
</div>

<div>
  <Avatar image={sampleImg} size="20"/>
</div>

<div>
  <Avatar image={sampleImg} size="32"/>
</div>

<div>
  <Avatar image={sampleImg} size="64"/>
</div>

