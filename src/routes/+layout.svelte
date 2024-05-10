<script lang="ts">
	import Slider from './Slider/Slider.svelte';
	import Header from './Header/Header.svelte';
	import Section from './Section/Section.svelte';
	import Competence from './Competence/Competence.svelte';
	import Projet from './Projet/Projet.svelte';
	import Contact from './Contact/Contact.svelte';
</script>

<Header />
<Slider />
<Section />
<Competence />
<Projet />
<Contact />
<slot />
