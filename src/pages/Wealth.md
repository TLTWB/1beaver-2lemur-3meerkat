---
import BaseHead from "../components/BaseHead.astro";
---
<!------
  /------------------
// Big SVG hero Name
//-------------------
//
// If you want to change your name you will have to recreate it
// in Figma or any other way you can export text as SVG
// After you have exported it, you have to remove the size atributes from the SVG
// this will allow the SVG become full width and full heigh. It will also be responsive.
--- -->
<section class="bg-primary">
  <div
    class="px-8 2xl:max-w-7xl mx-auto pt-12"
    data-aos="fade-up"
    data-aos-duration="2000">
    <svg class="text-secondary" viewBox="0 0 167 13" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M.58 3.477V1.091h9.481v2.386H6.78V12H3.86V3.477H.58ZM21.08 6.545c0 1.215-.236 2.24-.708 3.074-.473.83-1.11 1.461-1.913 1.89-.802.427-1.697.64-2.684.64-.995 0-1.893-.215-2.695-.644-.8-.434-1.435-1.066-1.907-1.897-.47-.834-.704-1.855-.704-3.063 0-1.214.235-2.237.704-3.068.472-.834 1.107-1.465 1.907-1.89.802-.43 1.7-.645 2.695-.645.987 0 1.882.215 2.684.644.803.426 1.44 1.057 1.913 1.891.472.831.708 1.854.708 3.068Zm-3.047 0c0-.653-.087-1.203-.26-1.65-.171-.452-.425-.793-.762-1.024-.334-.234-.746-.351-1.236-.351s-.904.117-1.241.351c-.334.231-.588.572-.762 1.023-.17.448-.256.998-.256 1.651 0 .654.085 1.206.256 1.657.174.447.428.788.762 1.023.337.23.75.346 1.24.346s.903-.115 1.237-.346c.337-.235.59-.575.761-1.023.174-.45.261-1.003.261-1.657ZM25.14 12V1.09H28.1v8.524h4.41V12H25.14Zm8.42 0V1.09h7.861v2.387h-4.9v1.875h4.495V7.74h-4.495v1.875H41.4V12h-7.84Zm8.882-8.523V1.091h9.481v2.386h-3.28V12h-2.92V3.477h-3.281Zm12.986 0V1.091h9.481v2.386h-3.28V12h-2.92V3.477h-3.281ZM65.874 12V1.09h2.962v4.262h3.92V1.091h2.962V12h-2.962V7.739h-3.92V12h-2.962Zm11.1 0V1.09h7.862v2.387h-4.9v1.875h4.495V7.74h-4.495v1.875h4.879V12h-7.84Zm14.79 0L88.545 1.09h3.303l1.491 6.713h.085l1.769-6.712h2.6l1.768 6.733h.085l1.491-6.733h3.303L101.224 12H98.39l-1.854-6.094h-.085L94.597 12h-2.834Zm23.365-5.455c0 1.215-.236 2.24-.708 3.074-.472.83-1.11 1.461-1.912 1.89-.803.427-1.698.64-2.685.64-.994 0-1.893-.215-2.695-.644-.799-.434-1.435-1.066-1.907-1.897-.469-.834-.703-1.855-.703-3.063 0-1.214.234-2.237.703-3.068.472-.834 1.108-1.465 1.907-1.89.802-.43 1.701-.645 2.695-.645.987 0 1.882.215 2.685.644.802.426 1.44 1.057 1.912 1.891.472.831.708 1.854.708 3.068Zm-3.046 0c0-.653-.087-1.203-.261-1.65-.171-.452-.425-.793-.762-1.024-.334-.234-.746-.351-1.236-.351s-.904.117-1.241.351c-.334.231-.588.572-.762 1.023-.17.448-.256.998-.256 1.651 0 .654.086 1.206.256 1.657.174.447.428.788.762 1.023.337.23.751.346 1.241.346.49 0 .902-.115 1.236-.346.337-.235.591-.575.762-1.023.174-.45.261-1.003.261-1.657ZM116.35 12V1.09h4.709c.809 0 1.518.148 2.125.443.607.295 1.079.72 1.417 1.273.337.554.506 1.218.506 1.992 0 .782-.174 1.44-.522 1.976a3.21 3.21 0 0 1-1.454 1.215c-.622.273-1.348.41-2.179.41h-2.813V6.098h2.216c.348 0 .645-.043.89-.128.249-.089.439-.229.57-.42.135-.192.202-.443.202-.752 0-.312-.067-.566-.202-.761a1.128 1.128 0 0 0-.57-.437 2.447 2.447 0 0 0-.89-.144h-1.044V12h-2.961Zm6.392-5.007L125.469 12h-3.217l-2.664-5.007h3.154ZM126.219 12V1.09h2.962v8.524h4.41V12h-7.372Zm12.617 0h-4.197V1.09h4.154c1.123 0 2.092.22 2.909.656a4.514 4.514 0 0 1 1.896 1.875c.448.813.671 1.788.671 2.924 0 1.137-.222 2.113-.666 2.93a4.562 4.562 0 0 1-1.885 1.875c-.813.433-1.774.65-2.882.65ZM137.6 9.486h1.129c.54 0 1-.087 1.38-.261.384-.174.675-.474.874-.9.202-.427.303-1.02.303-1.78s-.103-1.353-.309-1.779c-.202-.426-.5-.726-.895-.9-.39-.174-.87-.26-1.438-.26H137.6v5.88ZM148.328 12V1.09h4.73c.831 0 1.529.113 2.093.336.569.224.996.54 1.284.949.291.408.437.89.437 1.443 0 .401-.089.767-.266 1.097-.174.33-.42.608-.736.831-.316.22-.685.373-1.108.459v.106c.469.018.895.137 1.279.357.383.217.689.517.916.9.227.38.341.828.341 1.343 0 .596-.156 1.127-.469 1.592-.309.465-.749.831-1.321 1.098-.572.266-1.253.399-2.045.399h-5.135Zm2.961-2.365h1.385c.498 0 .87-.092 1.119-.277.249-.188.373-.465.373-.831 0-.256-.059-.472-.176-.65a1.094 1.094 0 0 0-.501-.405 1.935 1.935 0 0 0-.772-.138h-1.428v2.3Zm0-4.134h1.215c.259 0 .488-.04.687-.122.199-.082.353-.199.464-.352a.947.947 0 0 0 .17-.57c0-.337-.121-.594-.362-.772-.242-.181-.547-.272-.916-.272h-1.258v2.088ZM158.197 12V1.09h7.863v2.387h-4.901v1.875h4.496V7.74h-4.496v1.875h4.879V12h-7.841Z" fill="currentColor"/>
</svg>
  </div>
  <div class="px-8 2xl:max-w-7xl mx-auto pb-12">
    <div class="mt-6 space-y-2">
      <div
        class="h-0.5 bg-secondary"
        data-aos="fade-up"
        data-aos-duration="1000">
      </div>
      <div
        class="flex flex-col sm:flex-row gap-3 justify-between lg:items-center"
        data-aos="fade-up"
        data-aos-duration="1500">
        <div class="flex gap-3 items-center">
          <h3 class="text-secondary text-xs font-medium">
            <span>“Those who make peaceful revolution impossible will make violent revolution inevitable." </span>
          </h3>
          <span class="h-auto border-secondary border"></span>
          <span class="text-secondary text-xs font-semibold"
            >John F. Kennedy</span
          >
        </div>
        <div>
          <ul class="lg:items-center flex justify-between w-full gap-3 relative text-xs">
            <li>
              <a
                href="https://odysee.com/@TLTWB:b"
                class="hover:text-secondary/80 text-secondary"
                >Odysee</a
              >
            </li><li>
              <a
                href="https://www.reddit.com/user/TLTWB/"
                class="hover:text-secondary/80 text-secondary"
                >Reddit</svg
                ></a
              >
            </li><li>
              <a
                href="mailto:M@tltwb.com"
                class="hover:text-secondary/80 text-secondary"
                >Email</a
              >
            </li>
          </ul>
        </div>
      </div>
      <div
        class="h-1.5 bg-secondary"
        data-aos="fade-up"
        data-aos-duration="2000">
      </div>
      <div class="h-3 bg-secondary" data-aos="fade-up" data-aos-duration="2500">
      </div>
      <div class="h-6 bg-secondary" data-aos="fade-up" data-aos-duration="3000">
      </div>
      <div
        class="h-12 bg-secondary"
        data-aos="fade-up"
        data-aos-duration="3000">
      </div>
      <div
        class="h-24 bg-secondary flex items-end p-4"
        data-aos="fade-up"
        data-aos-duration="3000"
        data-aos-delay="150">
      </div>
    </div>
  </div>
</section>
