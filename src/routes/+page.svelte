<script>
  import logo from "../assets/logo.png";
  import "@fontsource/roboto";
  import { HomeScreen } from "../constants/constants";
</script>

<!--  -->
<div class="container w-full h-full mt-8 ml-2 md:ml-6">
  <div class="wrapper w-full mx-3 flex gap-6 h-auto overflow-x-hidden">
    <div class="left w-[150px] h-[129px] border border-gray-300 p-[2px]">
      <img src={logo} class="w-full h-auto min-w-[140px] min-h-[120px]" alt="projectLabPic" />
    </div>

    <div class="right w-[85%] h-auto flex flex-col gap-5">
      <h1 class="text-4xl">{HomeScreen.TITLE}</h1>
      <hr />
      <div class="container mx-auto">
        <!-- Section: Design Block -->
        <section class="mb-2">
          <div
            class="alert alert-dismissible fade show items-center justify-between rounded-md bg-[#fcf8e3] py-3.5 px-4 text-center text-black md:flex md:text-left border border-[#faebcc]"
          >
            <div
              class="mb-4 flex flex-wrap items-center justify-center md:mb-0 md:justify-start"
            >
              <!-- svelte-ignore a11y-missing-attribute -->
              <p class="text-[#8a6d3b] text-[17px]">{HomeScreen.MESSAGE}</p>
              <a
                href="/ad?assignmentId=debugRuNdu&hitId=debugOr0wK&workerId=debug0SdjT&mode=debug"
                class="ml-1 text-blue-600 font-semibold underline"
                >{HomeScreen.ANCHAR_TAG}</a
              >.
            </div>
          </div>
        </section>
        <!-- Section: Design Block -->
      </div>
    </div>
  </div>
</div>

<!-- styling section -->
<style>
  h1,
  p {
    font-family: "Roboto", sans-serif;
  }
</style>
