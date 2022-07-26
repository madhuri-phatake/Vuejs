      <template>
      <HelloWorld msg="welcome"/>
      <InterPolation/>
      <Events/>
      
      <two-way-binding1/>
      <GetValues/>
      <CheckboxandRadio/>
      <IfElsecondition></IfElsecondition>
      <for-Loop></for-Loop>


      </template>
      <script>
      import HelloWorld from './components/HelloWorld.vue';
      import InterPolation from './components/Interpolation.vue';
      import Events from './components/Events.vue';
      import TwoWayBinding1 from './components/TwoWayBinding.vue';
      import GetValues from './components/GetValues.vue';
      import CheckboxandRadio from './components/CheckboxandRadio.vue';
      import IfElsecondition from './components/IfElsecondition.vue';
      import ForLoop from './components/forLoop.vue';
      export default{
        name:"App",
      components:{  
        HelloWorld,
        InterPolation,
        Events,
        TwoWayBinding1,
        GetValues,
        CheckboxandRadio,
        IfElsecondition,
        ForLoop,
      }
      }
      </script>

      <!-- <script setup lang="ts">
      import { RouterLink, RouterView } from "vue-router";
      import HelloWorld from "./components/HelloWorld.vue";
      import Add from "./components/Add.vue";
      </script>

      <template>
        <header>
          <img
            alt="Vue logo"
            class="logo"
            src="@/assets/logo.svg"
            width="125"
            height="125"
          />
          <div class="wrapper">
            
            <HelloWorld msg="You did it!" />

            <nav>
              <RouterLink to="/">Home</RouterLink>
              <RouterLink to="/about">About</RouterLink>
            </nav>
          </div>
        </header>

        <RouterView />
      </template>

      <style scoped>
      header {
        line-height: 1.5;
        max-height: 100vh;
      }

      .logo {
        display: block;
        margin: 0 auto 2rem;
      }

      nav {
        width: 100%;
        font-size: 12px;
        text-align: center;
        margin-top: 2rem;
      }

      nav a.router-link-exact-active {
        color: var(--color-text);
      }

      nav a.router-link-exact-active:hover {
        background-color: transparent;
      }

      nav a {
        display: inline-block;
        padding: 0 1rem;
        border-left: 1px solid var(--color-border);
      }

      nav a:first-of-type {
        border: 0;
      }

      @media (min-width: 1024px) {
        header {
          display: flex;
          place-items: center;
          padding-right: calc(var(--section-gap) / 2);
        }

        .logo {
          margin: 0 2rem 0 0;
        }

        header .wrapper {
          display: flex;
          place-items: flex-start;
          flex-wrap: wrap;
        }

        nav {
          text-align: left;
          margin-left: -1rem;
          font-size: 1rem;

          padding: 1rem 0;
          margin-top: 1rem;
        }
      }
      </style> -->
