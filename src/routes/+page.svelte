<script>
	import AboutUs from "../components/AboutUs.svelte";
	import Appointment from "../components/Appointment.svelte";
	import Departments from "../components/Departments.svelte";
	import Questions from "../components/Questions.svelte";
  import Values from "../components/Values.svelte";

</script>
<body>
  <div class="hero min-h-screen" style="background-image:url(https://i.postimg.cc/RZXLF550/stock-photo-cropped-shot-of-a-female-nurse-hold-her-senior-patient-s-hand-giving-support-doctor-help.jpg);
    background-repeat: no-repeat; background-size: cover">
      <div class="hero-content  flex-col lg:flex-row-reverse">
        <h1 class="text-5xl font-bold text-indigo-800 pr-60 mr-72 mb-72">Your Best Friend to protect your Health</h1> 
      </div>
    </div>

  <div class="text-center">
      <h2 class="text-4xl font-bold text-indigo-800 py-20">Our Values</h2>
    </div>

    <Values/>
  <AboutUs/>

    <div class="text-center">
      <h2 class="text-4xl font-bold text-indigo-800 text-center py-20">Departaments</h2>
    </div>
    <Departments/>
   <div class="text-start py-20">
      <h2 class="text-3xl font-bold justify-start">Book an</h2>
      <h2 class="text-5xl font-bold justify-start text-indigo-800">Appointment</h2>
    </div>
    <Appointment/>
    <div class="text-center">
      <h2 class="text-2xl font-bold">What people</h2>
      <h2 class="text-4xl font-bold text-indigo-800">Asks</h2>
    </div>
    <Questions/>
</body>

