<script>
	const birthYear = 1995;
	let now = new Date(), month, day, year;
	const myAge = now.getFullYear() - birthYear;
</script>

<div class="hero min-h-screen bg-base-200">
    <div class="hero-content flex-col lg:flex-row">
      <img src="https://iili.io/H8TdgPR.jpg" class="max-w-sm rounded-lg shadow-2xl" alt=""/>
      <div>
        <h1 class="text-5xl font-bold">Hello!</h1>
        <p class="py-6">
					My name is Ahmad Dwi Sovana. Professionally, you can call me Dwi. I am a Software Engineer since the end of 2015. <br>
					Currently, I am living in Indonesia with my grandparent, we are taking care eachother.<br>
					This year, I am turning {myAge} years old, I am quite old now :)
					<br>
					<br>
					Reach me out here!
				</p>
      </div>
    </div>
</div>