<template>
  <div class="py-4 container-fluid">
    <div class="row mb-4">
      <div class="col-lg-12 position-relative z-index-2">
        <div class="row  p-2">
          <div class="card card1 col-lg-3 col-md-6 col-sm-6 mt-lg-0 mt-4 col mb-3 " style="width: 23rem; margin-left: 20px; border-radius: 25px; background-color: #59BCFF;">
            <div class="card-body mt-4 mb-2"  >
              <div class="d-inline-block float-left">
                <h2 class="mb-0"  >{{c1bnumber}}</h2>
                <p class="">{{c1description}}</p>
              </div>
              <span class="d-inline-block btn float-end">
                <svg style="width:50px;height:50px" viewBox="0 0 24 24">
                  <path fill="currentColor" d="M17,18L12,15.82L7,18V5H17M17,3H7A2,2 0 0,0 5,5V21L12,18L19,21V5C19,3.89 18.1,3 17,3Z" />
                </svg>
              </span>
            </div>
          </div> 
          <div class="card card2 col-lg-3 col-md-6 col-sm-6 mt-lg-0 mt-4 mb-3" style="width: 23rem; margin-left: 20px;  border-radius: 25px; background-color: #57F998" >
            <div class="card-body  mt-4">
              <div class="d-inline-block float-left">
                <h2 class="mb-0"  >{{c2bnumber}}</h2>
                <p class="">{{c2description}}</p>
              </div>
              <span class="d-inline-block btn float-end">
                <svg style="width:50px;height:50px" viewBox="0 0 24 24">
                  <path fill="currentColor" d="M19 3H18V1H16V3H8V1H6V3H5C3.9 3 3 3.9 3 5V19C3 20.11 3.9 21 5 21H19C20.11 21 21 20.11 21 19V5C21 3.9 20.11 3 19 3M19 19H5V9H19V19M5 7V5H19V7H5M10.56 17.46L16.5 11.53L15.43 10.47L10.56 15.34L8.45 13.23L7.39 14.29L10.56 17.46Z" />
                </svg>
              </span>
            </div>
          </div>
          <div class="card col-lg-3 col-md-6 col-sm-6 mt-lg-0 mt-4 mb-3" style="width: 23rem; margin-left: 20px; border-radius: 25px; background-color: #FDB765;" >
            <div class="card-body  mt-4">
              <div class="d-inline-block float-left">
                <h2 class="mb-0"  >{{c3bnumber}}</h2>
                <p class="">{{c3description}}</p>
              </div>
              <span class="d-inline-block btn float-end">
                <svg style="width:50px;height:50px" viewBox="0 0 24 24">
                  <path fill="currentColor" d="M14,12L10,8V11H2V13H10V16M20,18V6C20,4.89 19.1,4 18,4H6A2,2 0 0,0 4,6V9H6V6H18V18H6V15H4V18A2,2 0 0,0 6,20H18A2,2 0 0,0 20,18Z" />
                </svg>
              </span>
            </div>
          </div>
          <div class="card col-lg-3 col-md-6 col-sm-6 mt-lg-0 mt-4 mb-3" style="width: 23rem; margin-left: 20px; border-radius: 25px; background-color: #FF6D59;" >
            <div class="card-body  mt-4">
              <div class="d-inline-block float-left">
                <h2 class="mb-0"  >{{c4bnumber}}</h2>
                <p class="">{{c4description}}</p>
              </div>
              <span class="d-inline-block btn float-end">
                <svg style="width:50px;height:50px" viewBox="0 0 24 24">
                  <path fill="currentColor" d="M20 2H4C2.9 2 2 2.9 2 4V22L6 18H20C21.1 18 22 17.1 22 16V4C22 2.9 21.1 2 20 2M20 16H5.2L4 17.2V4H20V16M16 11V9H11.5L13.3 7.2L12 6L8 10L12 14L13.2 12.8L11.5 11H16Z" />
                </svg>
              </span>
            </div>
          </div>
          <div class="card col-lg-3" style="width: 23rem; margin-left: 20px; text-align: center; background-color: white;">
            <div class="card-body mt-4 mb-2">
              <div class="d-inline-block float-center">
                <span class="">
                <img src="../assets/img/adiobar.png" style="width:100px;height:75px" />
              </span>
                <h2 class="mb-0">785</h2>
                <p class="">Available Room Today</p>
              </div>
           </div>
          </div> 
          <div class="col-lg-3" style="text-align: center;" >
            <h5 style="font-family: Arial;">Reservation Statistic</h5>
            <p>Lorem ipsum dolor sit amet</p>
          </div>
          <div class="col-lg-3" style="text-align: center;" >
            <h5 style="font-family: Arial;"><span style="font-weight: bold;" >549</span> Check In</h5>
          </div>
          <div class="col-lg-3" style="text-align: center;" >
            <h5 style="font-family: Arial;"><span style="font-weight: bold;">327</span> Check Out</h5>
          </div>
          <div class="card col-lg-3" style="width: 23rem; margin-left: 20px; margin-top: 20px; height: 80%; text-align: left; background-color: white;">
            <div class="card-body mt-4 mb-2">
              <p class="">Booked Room Today</p>
              <div class="progress" style="background-color: white;">
                <div class="progress-bar bg-warning" role="progressbar" style="width: 50%" color="white" aria-valuenow="50"  aria-valuemin="0" aria-valuemax="100"></div>
              </div>
              <div class="progress" style="background-color: white;">
                <div class="progress-bar bg-success " role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
                <div class="progress" style="background-color: white;">
                <div class="progress-bar bg-danger" role="progressbar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
               <svg xmlns="http://www.w3.org/2000/svg" style="color:#F6943A" width="80" height="80" fill="currentColor" class="bi bi-dot" viewBox="6.5 6 20 15">
               <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z"/>
               <text color="black" x="10" y="9" font-size="2">Padding</text>
               <text color="black" x="9" y="18" font-size="5">234</text> 
              </svg>
               <svg xmlns="http://www.w3.org/2000/svg" style="color:#42AE94" width="80" height="80" fill="currentColor" class="bi bi-dot" viewBox="0 6 20 15">
               <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z"/>
               <text color="black" x="10" y="9" font-size="2">Done</text> 
               <text color="black" x="7" y="18" font-size="5">65</text> 
              </svg>
           
               <svg xmlns="http://www.w3.org/2000/svg" style="color:#9658C7" width="80" height="80" fill="currentColor" class="bi bi-dot" viewBox="0 4.5 16 16">
               <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z"/>
               <text color="black" x="10" y="9" font-size="2">Finish</text>
               <text color="black" x="8" y="16" font-size="4">763</text> 
              </svg>    
           </div>
           
          </div> 
          <div class="col-lg-9" style="margin-top: -10%;" >
          <apexchart
          height="487"
          type="area"
          :color="color"
         :options="chartOptions"
         :series="series"
        ></apexchart>
        </div> 

        <div  class="col-lg-6">
          <FullCalendar :options='calendarOptions' style="width: 100%;" />
        </div>
        <div class="card col-lg-6" style=" text-align: center; height: 30%; background-color: white;">
            <div class="card-body mt-4 mb-3">
              <div class="d-inline-block float-center">
                <img src="../assets/img/check1.png" style="width:250px;height:150px" />
              </div>
              <div class="d-inline-block float-center">
              <img src="../assets/img/check2.png" style="width:260px;height:160px" />
              </div>
           </div>
          </div>
          <h5 style="padding: 20px;">Newest Booking</h5>
  <div class="row row-cols-2 g-3 col-lg-6">
  <div class="col" >
    <div class="card">
      <img src="../assets/img/ssss.png" style="width:150px;height:80px" />
    </div>
  </div>
  <div class="col">
    <div class="card">
      <img src="../assets/img/louis.png" style="width:150px;height:80px" />
    </div>
  </div>
  <div class="col">
    <div class="card">
      <img src="../assets/img/richard.png" style="width:150px;height:80px" />
    </div>
  </div>
  <div class="col">
    <div class="card">
      <img src="../assets/img/bella.png" style="width:150px;height:80px" />
    </div>
  </div>
</div>
<div class="col-lg-6" style="margin-top: -25%;">
    <div class="card">
  <div class="card-body">
    <img src="../assets/img/ali.png" style="width:300px;height:80px" />
    <p class="card-text">I have been there many times.Rooms ,Food and Service are excellent.we did lots of Excursions and all the places are from the Hotel reachable. we visited Long Waterfall and was very helpful and excellent.</p>
  </div>
</div>
<div class="card">
  <div class="card-body">
    <img src="../assets/img/kena.png" style="width:300px;height:80px" />
  <p class="card-text">423px
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nos</p>
  </div>
</div>
<div class="card">
  <div class="card-body">
    <img src="../assets/img/china.png" style="width:300px;height:80px" />
    <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nos ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
  </div>
</div>
</div>
    </div>
        </div>
      </div>
    </div>
</template>
<script>
import FullCalendar from '@fullcalendar/vue3'
import dayGridPlugin from '@fullcalendar/daygrid'
import VueApexCharts from "vue3-apexcharts";
import logoXD from "@/assets/img/small-logos/logo-xd.svg";
import logoAtlassian from "@/assets/img/small-logos/logo-atlassian.svg";
import logoSlack from "@/assets/img/small-logos/logo-slack.svg";
import logoSpotify from "@/assets/img/small-logos/logo-spotify.svg";
import logoJira from "@/assets/img/small-logos/logo-jira.svg";
import logoInvision from "@/assets/img/small-logos/logo-invision.svg";

export default {
  name: "dashboard-default",
  data() {
    
    return {
      calendarOptions: {
        plugins: [dayGridPlugin],
        initialView: 'dayGridMonth',
        weekends: false,
     
      },
      c1description: 'New booking',
      c1bnumber: '872',
      c2description: 'Schedule Room',
      c2bnumber: '285',
      c3description: 'Check In',
      c3bnumber: '53',
      c4description: 'Check Out',
      c4bnumber: '78',
      logoXD,
      logoAtlassian,
      logoSlack,
      logoSpotify,
      logoJira,
      logoInvision,
      chartOptions: {
            chart: {
              height: 350,
              type: 'area'
            },
            dataLabels: {
              enabled: false
            },
            stroke: {
              curve: 'smooth'
            },
        xaxis: {
          categories: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12],
        },
      },
      series: [{
            name: 'series1',
            color: "#1362FC",
            data: [10, 10, 10,14, 30, 10, 10, 35,  10, 25, 45, 20]
          }, {
            color: "#FF6E5A",
            name: 'series2',
            data: [5, 7, 5, 7, 5, 7, 5, 7, 5, 7, 5, 7]
          }],
      
    };
    
  },
  components: {
    FullCalendar,
    apexchart: VueApexCharts,
  },
};

</script>
<style>
.card{
  margin: 0px;
  box-shadow: 5px 10px;
}

</style>