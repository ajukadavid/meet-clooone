<template>
  <nav class="container flex justify-between py-2 bg-white">
    <div class="flex items-center m-3">
      <img src="../static/ggle.png" />
      <div class="ml-1 -mt-2">
        <span class="text-2xl text-gray-600">Meet</span>
      </div>
    </div>
    <!-- left header section -->

    <!-- right header section -->
    <div class="flex items-center space-x-4">
       <div class="date mt-1 mr-5 text-gray-500 text-lg font-light">
      <span>{{ time }}</span>
      <span>{{ period }}</span>

     <span> • </span>
      <span>{{ day }},</span>


      <span>{{ month }}</span>
      <span>{{ date }}</span>
    </div>
      <a href="#">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          height="24px"
          viewBox="0 0 24 24"
          width="24px"
          fill="gray"
        >
          <path d="M0 0h24v24H0V0z" fill="none" />
          <path
            d="M11 18h2v-2h-2v2zm1-16C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm0-14c-2.21 0-4 1.79-4 4h2c0-1.1.9-2 2-2s2 .9 2 2c0 2-3 1.75-3 5h2c0-2.25 3-2.5 3-5 0-2.21-1.79-4-4-4z"
          />
        </svg>
      </a>
      <a href="#">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24px" fill="gray">
          <path d="M0 0h24v24H0V0z" fill="none" />
          <path
            d="M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H5.17L4 17.17V4h16v12zM11 5h2v6h-2zm0 8h2v2h-2z"
          />
        </svg>
      </a>
      <a href="#">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6 text-gray-500"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
          />
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
          />
        </svg>
      </a>
      <div class="last-two"></div>
      <a href="#">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 text-gray-500"
          fill="none"
          stroke="currentColor"
        >
          <path
            d="M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z"
          />
        </svg>
      </a>
      <a href="#" class="p-2 rounded-full bg-blue-50">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-6 h-6 text-gray-200"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
          />
        </svg>
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      time: '',
      period: '',
      day: '',
      month: '',
      date: '',
    }
  },
  created() {
    setInterval(this.getNow, 1000);
  },
  methods: {
    getNow: function () {
    var today = new Date();
    let days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday"]
    let mainDay = today.getDay()
    var months = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
    let mainMonth = today.getMonth()
    this.month = months[mainMonth].substring(0,3)
    this.day = days[mainDay].substring(0,3)

    this.time = today.getHours() + ' :' + today.getMinutes()


    function formatAMPM(date) {
  var hours = date.getHours();
  var minutes = date.getMinutes();
  var ampm = hours >= 12 ? 'PM' : 'AM';
  hours = hours % 12;
  hours = hours ? hours : 12; // the hour '0' should be '12'
  minutes = minutes < 10 ? '0'+minutes : minutes;
  var strTime = hours + ':' + minutes + ' ' + ampm;
  return strTime;
}

this.time = formatAMPM(today)
   this.date =  + today.getDate();

    }
  }
}


</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
nav {
  font-family: "Roboto", sans-serif;
}

</style>
