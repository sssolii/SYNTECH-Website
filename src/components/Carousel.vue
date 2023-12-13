<script lang="ts">
import Flicking from "@egjs/vue3-flicking";

export default {
  components: {
    Flicking: Flicking,
  },
};
</script>

<template>
  <Flicking :options="{}" style="height: 600px">
    <div style="width: 1100px">
      <div class="card">
        <div class="media">
          <div class="media-left">
            <div class="section">
              <figure class="image" style="width: 450px">
                <img 
                  src="../assets/img/rd poster.jpg"
                  alt="Placeholder image"
                />
              </figure>
            </div>
          </div>
          <div class="media-content">
            <div class="section">
              <p class="title">Recruitment Drive January Semester 2024</p>
              <p class="content">
                <p style="color:BLUE">UTP's STUDENT ONLY</p> 
                Interested in joining Syntech?, we are proud to announce we open for recruitment. Do register before the registrartion
                close with 3 department available HUGE, LEVEL, ACTION. No requirement for HUGE and ACTION. For LEVEL there are some 
                requirement needed to able to register. Click register now and see wether you are eligable or not.
              </p>
              <button 
                style="
                  font-weight: 600;
                  border-width: 2px;
                  color: black;
                  border-color: rgba(88, 188, 130, 0.6);
                "
                class="button is-primary is-outlined is-rounded"
              >
                REGISTER NOW
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div style="width: 25px"></div>
    <div style="width: 1100px">
      <div class="card">
        <div class="media">
          <div class="media-left">
            <div class="section">
              <figure class="image" style="width: 458px">
                <img
                  src="../assets/img/synhack 2023.jpg"
                  alt="Placeholder image"
                />
              </figure>
            </div>
          </div>
          <div class="media-content">
            <div class="section">
              <p class="title">Joke-A-Thorn</p>
              <p class="content">
                <p style="color:red">SYNTECH MEMBER ONLY</p> 
                Joke-A-Thorn january semester 2024 is now open, each team consist of 3 people will compete in a 24 hour programming challenge
                where they need to build a working system and pith to our judges. Click register now for more info.
              </p>
              <button
                class="button is-primary is-outlined is-rounded"
                style="
                  font-weight: 600;
                  border-width: 2px;
                  border-color: rgba(88, 188, 130, 0.6);
                  color: black;
                "
              >
                REGISTER NOW
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div style="width: 25px"></div>
    <div style="width: 1100px">
      <div class="card">
        <div class="media">
          <div class="media-left">
            <div class="section">
              <figure class="image" style="width: 459px">
                <img
                  src="../assets/img/cimb visit 23.jpg"
                  alt="Placeholder image"
                />
              </figure>
            </div>
          </div>
          <div class="media-content">
            <div class="section">
              <p class="title">Industrial Visit To CIMB </p>
              <p class="content">
                <p style="color:BLUE">UTP's STUDENT ONLY</p> 
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
              <button
                class="button is-primary is-outlined is-rounded"
                style="
                  font-weight: 600;
                  border-width: 2px;
                  border-color: rgba(88, 188, 130, 0.6);
                  color: black;
                "
              >
                REGISTER NOW
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div style="width: 25px"></div>
    <div style="width: 1100px">
      <div class="card">
        <div class="media">
          <div class="media-left">
            <div class="section">
              <figure class="image" style="width: 464px">
                <img
                  src="../assets/img/talk.jpg"
                  alt="Placeholder image"
                />
              </figure>
            </div>
          </div>
          <div class="media-content">
            <div class="section">
              <p class="title">Talk By The Industry</p>
              <p class="content">
                <p style="color:GREEN">OPEN CATEGORY</p> 
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
                in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
              <button
                class="button is-primary is-outlined is-rounded"
                style="
                  font-weight: 600;
                  border-width: 2px;
                  border-color: rgba(88, 188, 130, 0.6);
                  color: black;
                "
              >
                REGISTER NOW
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </Flicking>
</template>

<style scoped>
@import url("../../node_modules/@egjs/flicking/dist/flicking.css");

.card {
  background-color: rgba(
    88,
    188,
    130,
    0.1
  ); /* background-color: rgba(0, 119, 182, 0.1); for back to blue*/
  border-radius: 20px;
}
</style>
