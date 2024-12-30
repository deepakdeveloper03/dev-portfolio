<script>
	import {HeroSection,AboutMeSection, MyWorkSection,SkillSection,ContactSection} from "$components";

	const {data}=$props();

	//$inspect(data);

	let {workExperience, projects,skills} =data;

</script>
<HeroSection></HeroSection>
<AboutMeSection {workExperience}></AboutMeSection>
<MyWorkSection {projects} />
<SkillSection {skills}/>
<ContactSection/>