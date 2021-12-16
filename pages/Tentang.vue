<template>
  <div class="w-full max-w-[1440px] mx-auto">
    <div class="main px-6 md:px-32">
      <NavbarNew />
      <div class="grid md:grid-cols-2 gap-x-32 pt-20">
        <div class="md:text-6xl text-[40px] tracking-wide">
          <h2 class="pr-5 font-semibold">
            <span class="text-about">Tentang</span> kami HJ Corporate
          </h2>
        </div>
        <div
          class="
            text-detail
            md:pt-0
            pt-6
            tracking-wide
            leading-6
            text-base text-left
            font-normal
            text-[#404852]
          "
        >
          <p>
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam consequat sunt nostrud amet.
          </p>
          <p class="pt-3">
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam consequat sunt nostrud amet.
          </p>
        </div>
      </div>
      <div class="grid md:grid-cols-3 grid-cols-1 md:gap-x-8">
        <div>
          <img class="pt-20" src="../static/images/imgHeaderOne.svg" alt="" />
        </div>
        <div>
          <img
            class="md:pt-52 pt-10 w-full"
            src="../static/images/imgHeaderTwo.svg"
            alt=""
          />
        </div>
        <div>
          <img
            class="md:pt-36 pt-10 w-full"
            src="../static/images/imgHeaderThree.svg"
            alt=""
          />
        </div>
      </div>

      <div class="grid md:grid-cols-2 grid-cols-1 md:py-20 md:gap-x-24">
        <div class="">
          <VisiMisi />
        </div>
        <div class="imgVisi md:pt-0 pt-20">
          <img src="../static/images/imgVision.svg" alt="" />
        </div>
      </div>
      <!-- Member -->
      <div
        class="grupMember md:max-w-[526px] max-w-none md:mx-auto md:pt-0 pt-20"
      >
        <div class="md:text-center text-left">
          <h6 class="text-member text-lg font-semibold uppercase pb-4">
            Member Kami
          </h6>
          <h3 class="md:text-5xl text-3xl font-semibold pb-4">
            Anggota Terbaik Kami
          </h3>
          <p
            class="
              text-us text-[#404852] text-[16px]
              leading-[26px]
              tracking-[0.3px]
              font-normal
            "
          >
            Kami bekerja dengan orang-orang paling berbakat dari setiap bidang.
            Percayakan setiap projek anda kepada setiap ahli pada tim kami
          </p>
        </div>
      </div>
      <div class="pt-20 grid md:grid-cols-4 grid-cols-1 gap-x-8">
        <div class="">
          <div
            class="
              buttonImages
              flex
              items-center
              rounded-xl
              gap-x-4
              mb-4
              text-black
              hover:text-white
              border border-[#DEDEDE]
              bg-white
              hover:bg-[#187C79]
            "
          >
            <div class="set">
              <svg
                width="28"
                height="28"
                viewBox="0 0 28 28"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M14 0.133301C13.4112 0.133301 12.9333 0.611167 12.9333 1.19997V1.3833C12.9333 1.89317 12.5743 2.34807 12.0708 2.42913C11.8265 2.4686 11.5847 2.51432 11.3458 2.56872C10.8509 2.68178 10.3504 2.40157 10.1562 1.9333L10.0854 1.76663C9.86032 1.22263 9.2367 0.963417 8.69164 1.18955C8.14764 1.41462 7.88842 2.03823 8.11455 2.5833L8.18538 2.75413C8.38165 3.22347 8.2247 3.77908 7.79163 4.04788C7.58257 4.17802 7.3786 4.31435 7.17913 4.45622C6.76527 4.75168 6.19277 4.68443 5.8333 4.32497L5.70413 4.1958C5.28707 3.77873 4.6118 3.77873 4.1958 4.1958C3.7798 4.61287 3.7798 5.28813 4.1958 5.70413L4.32497 5.8333C4.68443 6.19277 4.75168 6.7642 4.45622 7.17913C4.31435 7.3786 4.17802 7.58257 4.04788 7.79163C3.77908 8.2247 3.22245 8.38267 2.75205 8.18747L2.5833 8.11663C2.0393 7.89157 1.4136 8.14972 1.18747 8.69372C0.962401 9.23772 1.22055 9.86133 1.76455 10.0875L1.93122 10.1562C2.39948 10.3504 2.68178 10.8509 2.56872 11.3458C2.51432 11.5847 2.46652 11.8265 2.42705 12.0708C2.34705 12.5732 1.89317 12.9333 1.3833 12.9333H1.19997C0.611167 12.9333 0.133301 13.4112 0.133301 14C0.133301 14.5888 0.611167 15.0666 1.19997 15.0666H1.3833C1.89317 15.0666 2.34807 15.4257 2.42913 15.9291C2.4686 16.1734 2.51432 16.4152 2.56872 16.6541C2.68178 17.1491 2.40157 17.6496 1.9333 17.8437L1.76663 17.9146C1.22263 18.1396 0.963417 18.7632 1.18955 19.3083C1.41462 19.8523 2.03823 20.1115 2.5833 19.8854L2.75413 19.8146C3.22453 19.6194 3.7801 19.7763 4.04997 20.2083C4.1801 20.4174 4.31537 20.6224 4.4583 20.8229C4.75377 21.2368 4.68652 21.8093 4.32705 22.1687L4.1958 22.2979C3.77873 22.715 3.77873 23.3902 4.1958 23.8062C4.61287 24.2222 5.28813 24.2233 5.70413 23.8062L5.83538 23.6771C6.19485 23.3176 6.76527 23.2483 7.17913 23.5437C7.37967 23.6867 7.58465 23.824 7.79372 23.9541C8.22572 24.2229 8.38475 24.7796 8.18955 25.25L8.11872 25.4187C7.89365 25.9627 8.1518 26.5884 8.6958 26.8146C9.2398 27.0396 9.86342 26.7815 10.0896 26.2375L10.1583 26.0708C10.3524 25.6025 10.853 25.3202 11.3479 25.4333C11.5868 25.4877 11.8286 25.5355 12.0729 25.575C12.5732 25.6528 12.9333 26.1068 12.9333 26.6166V26.8C12.9333 27.3888 13.4112 27.8666 14 27.8666C14.5888 27.8666 15.0666 27.3888 15.0666 26.8V26.6166C15.0666 26.1068 15.4257 25.6519 15.9291 25.5708C16.1734 25.5313 16.4152 25.4856 16.6541 25.4312C17.1491 25.3182 17.6496 25.5984 17.8437 26.0666L17.9146 26.2333C18.1396 26.7773 18.7632 27.0365 19.3083 26.8104C19.8523 26.5853 20.1115 25.9617 19.8854 25.4166L19.8146 25.2458C19.6194 24.7754 19.7763 24.2198 20.2083 23.95C20.4174 23.8198 20.6224 23.6846 20.8229 23.5416C21.2368 23.2462 21.8093 23.3134 22.1687 23.6729L22.2979 23.8041C22.715 24.2212 23.3902 24.2212 23.8062 23.8041C24.2222 23.3871 24.2233 22.7118 23.8062 22.2958L23.6771 22.1646C23.3176 21.8051 23.2483 21.2347 23.5437 20.8208C23.6867 20.6203 23.824 20.4153 23.9541 20.2062C24.2229 19.7742 24.7796 19.6152 25.25 19.8104L25.4187 19.8812C25.9627 20.1063 26.5884 19.8481 26.8146 19.3041C27.0396 18.7601 26.7815 18.1365 26.2375 17.9104L26.0708 17.8416C25.6025 17.6475 25.3202 17.147 25.4333 16.6521C25.4877 16.4131 25.5355 16.1713 25.575 15.9271C25.6528 15.4268 26.1068 15.0666 26.6166 15.0666H26.8C27.3888 15.0666 27.8666 14.5888 27.8666 14C27.8666 13.4112 27.3888 12.9333 26.8 12.9333H26.6166C26.1068 12.9333 25.6519 12.5743 25.5708 12.0708C25.5313 11.8265 25.4856 11.5847 25.4312 11.3458C25.3182 10.8509 25.5984 10.3504 26.0666 10.1562L26.2333 10.0854C26.7773 9.86032 27.0365 9.2367 26.8104 8.69164C26.5853 8.14764 25.9617 7.88842 25.4166 8.11455L25.2458 8.18538C24.7754 8.38058 24.2198 8.22363 23.95 7.79163C23.8198 7.58257 23.6846 7.37758 23.5416 7.17705C23.2462 6.76318 23.3134 6.19068 23.6729 5.83122L23.8041 5.70205C24.2212 5.28498 24.2212 4.60972 23.8041 4.19372C23.3871 3.77665 22.7118 3.77665 22.2958 4.19372L22.1666 4.32497C21.8072 4.68443 21.2347 4.75377 20.8208 4.4583C20.6203 4.31537 20.4153 4.17802 20.2062 4.04788C19.7742 3.77908 19.6173 3.22245 19.8125 2.75205L19.8833 2.5833C20.1084 2.0393 19.8502 1.4136 19.3062 1.18747C18.7622 0.962401 18.1386 1.22055 17.9125 1.76455L17.8416 1.93122C17.6475 2.39948 17.147 2.68178 16.6521 2.56872C16.4131 2.51432 16.1713 2.46652 15.9271 2.42705C15.4257 2.34705 15.0666 1.89317 15.0666 1.3833V1.19997C15.0666 0.611167 14.5888 0.133301 14 0.133301ZM14 5.46663C18.3505 5.46663 21.9345 8.72517 22.4604 12.9333H15.8437C15.6568 12.6095 15.3881 12.3406 15.0645 12.1534C14.7409 11.9662 14.3738 11.8673 14 11.8666C13.9993 11.8666 13.9986 11.8666 13.9979 11.8666L10.6896 6.1333C11.7077 5.70421 12.8258 5.46663 14 5.46663ZM8.84788 7.2083L12.1541 12.9333C11.9663 13.2574 11.8671 13.6253 11.8666 14C11.8679 14.3732 11.967 14.7395 12.1541 15.0625L8.8458 20.7896C6.79615 19.2309 5.46663 16.7734 5.46663 14C5.46663 11.2255 6.79691 8.76686 8.84788 7.2083ZM15.8458 15.0666H22.4604C21.9345 19.2748 18.3505 22.5333 14 22.5333C12.8258 22.5333 11.7077 22.2957 10.6896 21.8666L13.9979 16.1333C13.9986 16.1333 13.9993 16.1333 14 16.1333C14.3742 16.133 14.7417 16.0343 15.0657 15.8471C15.3897 15.6598 15.6587 15.3907 15.8458 15.0666Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div>
              <h3 class="font-semibold">Founders</h3>
            </div>
          </div>
          <div
            class="
              buttonImages
              border border-[#DEDEDE]
              flex
              items-center
              rounded-xl
              gap-x-4
              mb-4
              text-black
              bg-white
              hover:bg-[#187C79] hover:text-white
            "
          >
            <div class="set pl-6">
              <svg
                width="22"
                height="22"
                viewBox="0 0 28 28"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M14 0.133301C13.4112 0.133301 12.9333 0.611167 12.9333 1.19997V1.3833C12.9333 1.89317 12.5743 2.34807 12.0708 2.42913C11.8265 2.4686 11.5847 2.51432 11.3458 2.56872C10.8509 2.68178 10.3504 2.40157 10.1562 1.9333L10.0854 1.76663C9.86032 1.22263 9.2367 0.963417 8.69164 1.18955C8.14764 1.41462 7.88842 2.03823 8.11455 2.5833L8.18538 2.75413C8.38165 3.22347 8.2247 3.77908 7.79163 4.04788C7.58257 4.17802 7.3786 4.31435 7.17913 4.45622C6.76527 4.75168 6.19277 4.68443 5.8333 4.32497L5.70413 4.1958C5.28707 3.77873 4.6118 3.77873 4.1958 4.1958C3.7798 4.61287 3.7798 5.28813 4.1958 5.70413L4.32497 5.8333C4.68443 6.19277 4.75168 6.7642 4.45622 7.17913C4.31435 7.3786 4.17802 7.58257 4.04788 7.79163C3.77908 8.2247 3.22245 8.38267 2.75205 8.18747L2.5833 8.11663C2.0393 7.89157 1.4136 8.14972 1.18747 8.69372C0.962401 9.23772 1.22055 9.86133 1.76455 10.0875L1.93122 10.1562C2.39948 10.3504 2.68178 10.8509 2.56872 11.3458C2.51432 11.5847 2.46652 11.8265 2.42705 12.0708C2.34705 12.5732 1.89317 12.9333 1.3833 12.9333H1.19997C0.611167 12.9333 0.133301 13.4112 0.133301 14C0.133301 14.5888 0.611167 15.0666 1.19997 15.0666H1.3833C1.89317 15.0666 2.34807 15.4257 2.42913 15.9291C2.4686 16.1734 2.51432 16.4152 2.56872 16.6541C2.68178 17.1491 2.40157 17.6496 1.9333 17.8437L1.76663 17.9146C1.22263 18.1396 0.963417 18.7632 1.18955 19.3083C1.41462 19.8523 2.03823 20.1115 2.5833 19.8854L2.75413 19.8146C3.22453 19.6194 3.7801 19.7763 4.04997 20.2083C4.1801 20.4174 4.31537 20.6224 4.4583 20.8229C4.75377 21.2368 4.68652 21.8093 4.32705 22.1687L4.1958 22.2979C3.77873 22.715 3.77873 23.3902 4.1958 23.8062C4.61287 24.2222 5.28813 24.2233 5.70413 23.8062L5.83538 23.6771C6.19485 23.3176 6.76527 23.2483 7.17913 23.5437C7.37967 23.6867 7.58465 23.824 7.79372 23.9541C8.22572 24.2229 8.38475 24.7796 8.18955 25.25L8.11872 25.4187C7.89365 25.9627 8.1518 26.5884 8.6958 26.8146C9.2398 27.0396 9.86342 26.7815 10.0896 26.2375L10.1583 26.0708C10.3524 25.6025 10.853 25.3202 11.3479 25.4333C11.5868 25.4877 11.8286 25.5355 12.0729 25.575C12.5732 25.6528 12.9333 26.1068 12.9333 26.6166V26.8C12.9333 27.3888 13.4112 27.8666 14 27.8666C14.5888 27.8666 15.0666 27.3888 15.0666 26.8V26.6166C15.0666 26.1068 15.4257 25.6519 15.9291 25.5708C16.1734 25.5313 16.4152 25.4856 16.6541 25.4312C17.1491 25.3182 17.6496 25.5984 17.8437 26.0666L17.9146 26.2333C18.1396 26.7773 18.7632 27.0365 19.3083 26.8104C19.8523 26.5853 20.1115 25.9617 19.8854 25.4166L19.8146 25.2458C19.6194 24.7754 19.7763 24.2198 20.2083 23.95C20.4174 23.8198 20.6224 23.6846 20.8229 23.5416C21.2368 23.2462 21.8093 23.3134 22.1687 23.6729L22.2979 23.8041C22.715 24.2212 23.3902 24.2212 23.8062 23.8041C24.2222 23.3871 24.2233 22.7118 23.8062 22.2958L23.6771 22.1646C23.3176 21.8051 23.2483 21.2347 23.5437 20.8208C23.6867 20.6203 23.824 20.4153 23.9541 20.2062C24.2229 19.7742 24.7796 19.6152 25.25 19.8104L25.4187 19.8812C25.9627 20.1063 26.5884 19.8481 26.8146 19.3041C27.0396 18.7601 26.7815 18.1365 26.2375 17.9104L26.0708 17.8416C25.6025 17.6475 25.3202 17.147 25.4333 16.6521C25.4877 16.4131 25.5355 16.1713 25.575 15.9271C25.6528 15.4268 26.1068 15.0666 26.6166 15.0666H26.8C27.3888 15.0666 27.8666 14.5888 27.8666 14C27.8666 13.4112 27.3888 12.9333 26.8 12.9333H26.6166C26.1068 12.9333 25.6519 12.5743 25.5708 12.0708C25.5313 11.8265 25.4856 11.5847 25.4312 11.3458C25.3182 10.8509 25.5984 10.3504 26.0666 10.1562L26.2333 10.0854C26.7773 9.86032 27.0365 9.2367 26.8104 8.69164C26.5853 8.14764 25.9617 7.88842 25.4166 8.11455L25.2458 8.18538C24.7754 8.38058 24.2198 8.22363 23.95 7.79163C23.8198 7.58257 23.6846 7.37758 23.5416 7.17705C23.2462 6.76318 23.3134 6.19068 23.6729 5.83122L23.8041 5.70205C24.2212 5.28498 24.2212 4.60972 23.8041 4.19372C23.3871 3.77665 22.7118 3.77665 22.2958 4.19372L22.1666 4.32497C21.8072 4.68443 21.2347 4.75377 20.8208 4.4583C20.6203 4.31537 20.4153 4.17802 20.2062 4.04788C19.7742 3.77908 19.6173 3.22245 19.8125 2.75205L19.8833 2.5833C20.1084 2.0393 19.8502 1.4136 19.3062 1.18747C18.7622 0.962401 18.1386 1.22055 17.9125 1.76455L17.8416 1.93122C17.6475 2.39948 17.147 2.68178 16.6521 2.56872C16.4131 2.51432 16.1713 2.46652 15.9271 2.42705C15.4257 2.34705 15.0666 1.89317 15.0666 1.3833V1.19997C15.0666 0.611167 14.5888 0.133301 14 0.133301ZM14 5.46663C18.3505 5.46663 21.9345 8.72517 22.4604 12.9333H15.8437C15.6568 12.6095 15.3881 12.3406 15.0645 12.1534C14.7409 11.9662 14.3738 11.8673 14 11.8666C13.9993 11.8666 13.9986 11.8666 13.9979 11.8666L10.6896 6.1333C11.7077 5.70421 12.8258 5.46663 14 5.46663ZM8.84788 7.2083L12.1541 12.9333C11.9663 13.2574 11.8671 13.6253 11.8666 14C11.8679 14.3732 11.967 14.7395 12.1541 15.0625L8.8458 20.7896C6.79615 19.2309 5.46663 16.7734 5.46663 14C5.46663 11.2255 6.79691 8.76686 8.84788 7.2083ZM15.8458 15.0666H22.4604C21.9345 19.2748 18.3505 22.5333 14 22.5333C12.8258 22.5333 11.7077 22.2957 10.6896 21.8666L13.9979 16.1333C13.9986 16.1333 13.9993 16.1333 14 16.1333C14.3742 16.133 14.7417 16.0343 15.0657 15.8471C15.3897 15.6598 15.6587 15.3907 15.8458 15.0666Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div>
              <h3 class="font-semibold">HJ Tech</h3>
            </div>
          </div>
          <div
            class="
              buttonImages
              text-black
              hover:text-white
              border border-[#DEDEDE]
              bg-white
              hover:bg-[#187C79]
              flex
              items-center
              rounded-xl
              gap-x-4
              mb-4
            "
          >
            <div class="set pl-6">
              <svg
                width="22"
                height="22"
                viewBox="0 0 28 28"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
              >
                <rect width="32" height="32" fill="url(#pattern0)" />
                <defs>
                  <pattern
                    id="pattern0"
                    patternContentUnits="objectBoundingBox"
                    width="1"
                    height="1"
                  >
                    <use
                      xlink:href="#image0_405_654"
                      transform="scale(0.0166667)"
                      fill="currentColor"
                    />
                  </pattern>
                  <image
                    id="image0_405_654"
                    width="60"
                    height="60"
                    xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADwAAAA8CAYAAAA6/NlyAAAABmJLR0QA/wD/AP+gvaeTAAAC2UlEQVRoge2avW4UMRDHfx0pkE68AtWJj4qTgvIcQAoeAl0VqLIFEjwREmUCSCmockkLTxB0ogFxSKEwBseZ3bXHH7sH+5dWSi7eGf8yHn+MDyZNmvQ/awGsgC/AcuC+FNcDDOil87wetEcFtQusuQprn6aC/yfAB+ArcA68BG6UctYFWwP6sMXnEXAzt7M22O/CZyWgG8GP+xyTEboNtun5Wy71wbqRTh7eIUCloUOBLzE5rVYMSFt+1YY+0zqIgd0HNh2dqAm91hjOCVsb+n2swdh89IE3mOGtzekmoF0X9KMAH3+0UHbUQm9+/wy6iawJbOe3tc9hzzvXdBbZQVf7/IW1kiayE2BHeF8CiIFWpcyF5/AbJlIaSbl9AsyEtl1DNARaPT8sBYdr4qFzweae8EQdCA7XwMPA9x9zHfYjcEtoG7OhKHoakzoSEul75I3sVkTafS9HZKtGOgW6BKxq6YmVdnhLp5ZU2BoFBiB9IoMtiKyvFOitg7XSQG8trJUE8Dai7Shztk+ll55RRNZXQ95NRV9ki5ViY1Rr6Zlh/rmjGeJWJYaxhbVtRnPDUQN2NNA1YQeHHgJ2MOiSE5TbLrUwmEUlYHeQYVMKg1lUcgfl2nZhrUrfcHR2KFfO+joAfgJPvc+l8lHRnK65N77r/V77hmPwg0DuG45O7QE/BMMpsDPMKSumBBxzw5H8RZs58EYwrIW1s3Fs3Vu64djFXBq4fi8ibHbqnDRYaenRFPtdSem2SrDXazw2Z7WFwRhbC4UtUXPBgXbpkTqaWhhMHS2ibgPPMJfPGlir3IXBJFjpSlOSO5FplgNNx4tE9jlhO5c5ZslKqUHFRLrYMD4lPGp7qc4IAykGe8czWuvc2RXpohPUK8F4rXOnBCZ9vTHrbPzJM74CXhA+kaWqb63PvvS8Az5jhvL9nIYj1AZdZJ0di/yc/qdhrZaYb9+fknG7OGnSpO3TLy374lENFDyIAAAAAElFTkSuQmCC"
                  />
                </defs>
              </svg>
            </div>
            <div>
              <h3 class="font-semibold">HJ Design</h3>
            </div>
          </div>
          <div
            class="
              buttonImages
              text-black
              hover:text-white
              border border-[#DEDEDE]
              bg-white
              hover:bg-[#187C79]
              flex
              items-center
              rounded-xl
              gap-x-4
              mb-4
            "
          >
            <div class="set pl-6">
              <svg
                width="22"
                height="22"
                viewBox="0 0 28 28"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M13.8666 4.2666C7.98502 4.2666 3.19995 8.3338 3.19995 13.3333C3.19995 15.0282 3.74542 16.6644 4.78328 18.0937L4.16245 22.9499L8.45203 21.1479C9.8301 21.8382 11.3723 22.2348 12.9833 22.3479C13.7725 25.4884 17.0502 27.7333 20.7999 27.7333C22.3493 27.7333 23.757 27.2945 24.9916 26.6333L28.0937 28.3749L27.6208 24.3562C28.3241 23.343 28.7999 22.1712 28.7999 20.8874C28.7999 18.1525 26.9653 15.8805 24.377 14.7729C24.4702 14.2915 24.5333 13.8104 24.5333 13.3333C24.5333 8.3338 19.7482 4.2666 13.8666 4.2666ZM10.2 9.78327C11.0298 9.78327 11.7 10.4535 11.7 11.2812C11.7 12.1089 11.0288 12.7833 10.2 12.7833C9.37115 12.7833 8.69995 12.1111 8.69995 11.2812C8.69995 10.4535 9.37115 9.78327 10.2 9.78327ZM18.3833 9.78327C19.2121 9.78327 19.8833 10.4535 19.8833 11.2812C19.8833 12.1111 19.2121 12.7833 18.3833 12.7833C17.5524 12.7833 16.8833 12.1111 16.8833 11.2812C16.8833 10.4524 17.5545 9.78327 18.3833 9.78327ZM20.7999 16.177C24.1489 16.177 26.6666 18.3876 26.6666 20.8874C26.6666 21.835 26.3228 22.7124 25.6979 23.4729L25.4104 23.8229L25.4625 24.2729L25.4854 24.4645L25.0124 24.1999L24.4708 24.5499C23.4745 25.1969 22.2009 25.5999 20.7999 25.5999C17.451 25.5999 14.9333 23.3873 14.9333 20.8874C14.9333 18.3889 17.4512 16.177 20.7999 16.177ZM18.1187 18.5916C17.4894 18.5916 16.9833 19.0998 16.9833 19.727C16.9833 20.3542 17.4904 20.8645 18.1187 20.8645C18.7448 20.8645 19.2551 20.3542 19.2562 19.727C19.2562 19.0998 18.7459 18.5916 18.1187 18.5916ZM23.502 18.5916C22.8759 18.5916 22.3666 19.0998 22.3666 19.727C22.3666 20.3542 22.8748 20.8645 23.502 20.8645C24.1303 20.8645 24.6416 20.3542 24.6416 19.727C24.6416 19.0998 24.1303 18.5916 23.502 18.5916Z"
                  fill="currentColor"
                />
              </svg>
            </div>
            <div>
              <h3 class="font-semibold">HJ Consultant</h3>
            </div>
          </div>
          <div
            class="
              buttonImages
              text-black
              hover:text-white
              border border-[#DEDEDE]
              bg-white
              hover:bg-[#187C79]
              flex
              items-center
              rounded-xl
              gap-x-4
            "
          >
            <div>
              <img class="pl-6" src="../static/images/imgCow.svg" alt="" />
            </div>
            <div>
              <h3 class="font-semibold">HJ Farm</h3>
            </div>
          </div>
        </div>
        <!-- Col 2 -->
        <div class="md:pt-0 pt-20">
          <div
            class="
              mb-10
              w-full
              bg-white
              hover:bg-[#FBFEFE]
              border border-[#DEDEDE]
              hover:border-[#146764]
              rounded-lg
              sahdow-lg
              p-12
              flex flex-col
              justify-center
              items-center
            "
          >
            <div class="mb-6">
              <img
                class="object-center object-cover rounded-full h-28 w-28"
                src="../static/images/imgAvatarOne.svg"
                alt="photo"
              />
            </div>
            <div class="text-center">
              <p class="text-2xl text-black font-semibold mb-2">Zuckerberg</p>
              <p class="text-base text-gray-400 font-normal">Founder</p>
            </div>
            <div class="grid grid-cols-3 gap-x-4 mt-10">
              <a href="">
                <img src="../static/images/imgLinkedin.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgInstgra.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgTwitter.svg" alt="" />
              </a>
            </div>
          </div>
          <div
            class="
              mb-10
              w-full
              bg-white
              hover:bg-[#FBFEFE]
              border border-[#DEDEDE]
              hover:border-[#146764]
              rounded-lg
              sahdow-lg
              p-12
              flex flex-col
              justify-center
              items-center
            "
          >
            <div class="mb-6">
              <img
                class="object-center object-cover rounded-full h-28 w-28"
                src="../static/images/imgPeopleTwo.svg"
                alt="photo"
              />
            </div>
            <div class="text-center">
              <p class="text-2xl text-black font-semibold mb-2">Hamilton</p>
              <p class="text-base text-gray-400 font-normal">Founder</p>
            </div>
            <div class="grid grid-cols-3 gap-x-4 mt-10">
              <a href="">
                <img src="../static/images/imgLinkedin.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgInstgra.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgTwitter.svg" alt="" />
              </a>
            </div>
          </div>
        </div>
        <!-- Col 3 -->
        <div class="">
          <div
            class="
              mb-10
              w-full
              bg-white
              hover:bg-[#FBFEFE]
              border border-[#DEDEDE]
              hover:border-[#146764]
              rounded-lg
              sahdow-lg
              p-12
              flex flex-col
              justify-center
              items-center
            "
          >
            <div class="mb-6">
              <img
                class="object-center object-cover rounded-full h-28 w-28"
                src="../static/images/imgPeopleThree.svg"
                alt="photo"
              />
            </div>
            <div class="text-center">
              <p class="text-2xl text-black font-semibold mb-2">Bambang</p>
              <p class="text-base text-gray-400 font-normal">Founder</p>
            </div>
            <div class="grid grid-cols-3 gap-x-4 mt-10">
              <a href="">
                <img src="../static/images/imgLinkedin.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgInstgra.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgTwitter.svg" alt="" />
              </a>
            </div>
          </div>
          <div
            class="
              mb-10
              w-full
              bg-white
              hover:bg-[#FBFEFE]
              border border-[#DEDEDE]
              hover:border-[#146764]
              rounded-lg
              sahdow-lg
              p-12
              flex flex-col
              justify-center
              items-center
            "
          >
            <div class="mb-6">
              <img
                class="object-center object-cover rounded-full h-28 w-28"
                src="../static/images/imgPeopleFour.svg"
                alt="photo"
              />
            </div>
            <div class="text-center">
              <p class="text-2xl text-black font-semibold mb-2">Nakamura</p>
              <p class="text-base text-gray-400 font-normal">Founder</p>
            </div>
            <div class="grid grid-cols-3 gap-x-4 mt-10">
              <a href="">
                <img src="../static/images/imgLinkedin.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgInstgra.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgTwitter.svg" alt="" />
              </a>
            </div>
          </div>
        </div>
        <!-- Col 4 -->
        <div class="">
          <div
            class="
              mb-10
              w-full
              bg-white
              hover:bg-[#FBFEFE]
              border border-[#DEDEDE]
              hover:border-[#146764]
              rounded-lg
              sahdow-lg
              p-12
              flex flex-col
              justify-center
              items-center
            "
          >
            <div class="mb-6">
              <img
                class="object-center object-cover rounded-full h-28 w-28"
                src="../static/tentang/imgFive.svg"
                alt="photo"
              />
            </div>
            <div class="text-center">
              <p class="text-2xl text-black font-semibold mb-2">Khoirul</p>
              <p class="text-base text-gray-400 font-normal">Founder</p>
            </div>
            <div class="grid grid-cols-3 gap-x-4 mt-10">
              <a href="">
                <img src="../static/images/imgLinkedin.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgInstgra.svg" alt="" />
              </a>
              <a href="">
                <img src="../static/images/imgTwitter.svg" alt="" />
              </a>
            </div>
          </div>
          <div
            class="
              textFounder
              mb-10
              w-full
              bg-white
              hover:bg-[#FBFEFE]
              border border-[#DEDEDE]
              hover:border-[#146764]
              rounded-lg
              sahdow-lg
              px-4
              flex flex-col
              justify-center
              items-center
            "
          >
            <p class="text-center">
              Jika, anda ingin bergabung bersama kami bisa lihat info mengenai
              <a href=""
                ><span class="text-green-700 hover:underline"
                  >karir disini</span
                ></a
              >
            </p>
          </div>
        </div>
      </div>

      <!-- Contact -->
      <div
        class="
          bgColor
          md:flex
          rounded-lg
          pt-14
          md:px-[97px]
          px-8
          md:pb-[60px]
          pb-52
        "
      >
        <div>
          <h1
            class="md:text-6xl text-3xl font-semibold md:pb-0 pb-8 text-white"
          >
            Percayakan produk anda pada <span class="textWe">kami</span>
          </h1>
        </div>
        <div>
          <p class="text-base text-white font-normal">
            Setiap anggota dalam tim kami memiliki keahlian yang tidak diragukan
            lagi, kami siap melayani projek anda sesuai dengan permintaan yang
            diberikan.
          </p>
          <button
            class="
              flex
              mt-8
              py-2
              px-6
              border border-white
              rounded-lg
              font-medium
              text-white
              hover:text-black hover:bg-white
              mx-1
            "
          >
            Kontak Kami
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 ml-4"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M17 8l4 4m0 0l-4 4m4-4H3"
              />
            </svg>
          </button>
        </div>
      </div>

      <!-- Footer -->
      <div>
        <hr class="md:mt-10 mt-12 mb-12" />
        <div class="flex md:flex-row flex-col-reverse px-6">
          <div class="col md:w-1/3 w-full md:pb-0 pb-14 text-left font-medium">
            <p>&copy;2021 HJ Corporate</p>
          </div>
          <div class="col md:w-1/3 md:pb-0 pb-6 w-full text-left font-semibold">
            <p>Sinduharjo, Kab. Sleman, Yogyakarta</p>
          </div>
          <div
            class="
              col
              md:w-1/3
              w-full
              md:gap-x-4
              gap-x-6
              md:pb-0
              pb-6
              flex
              md:justify-end
              justify-start
              md:mb-20
              mb-0
            "
          >
            <a href="">
              <img
                class="
                  hover:text-black hover:opacity-[100%]
                  opacity-[30%]
                  scale-75
                "
                src="../static/tentang/emailFoot.png"
                alt=""
              />
            </a>
            <a href="">
              <img
                class="hover:text-black hover:opacity-[100%] opacity-[30%]"
                src="../static/tentang/linkeFoot.png"
                alt=""
              />
            </a>
            <a href="">
              <img
                class="hover:text-black hover:opacity-[100%] opacity-[30%]"
                src="../static/tentang/fbFoot.png"
                alt=""
              />
            </a>
            <a href="">
              <img
                class="hover:text-black hover:opacity-[100%] opacity-[30%]"
                src="../static/tentang/instaFoot.png"
                alt=""
              />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VisiMisi from "../components/VisiMisi.vue";
export default {
  name: "Tentang",
  data() {},
  components: {
    VisiMisi,
  },
};
</script>

<style>
* {
  font-family: "Poppins", sans-serif;
  box-sizing: border-box;
  margin: 0;
  scroll-behavior: smooth;
}

.main {
  max-width: 1440px;
}

.text-about {
  color: #146764;
}

.text-member {
  color: #187c79;
}

.buttonImages {
  width: full;
  height: 56px;
}

.imgSetting:hover {
  fill: #fff;
}

.textWe {
  color: #c4b88c;
}

.imgVisi {
  height: 520px;
  width: auto;
}
.textFounder {
  padding-top: 148px;
  padding-bottom: 150px;
}
.set svg:hover,
path:hover,
#pattern0 use:hover {
  fill: white;
}

.bgColor {
  background-image: url("../static/tentang/bgColor.png");
  background-position: right bottom;
  background-size: cover;
}

@media screen and (max-width: 768px) {
  .bgColor {
    background-position: top;
  }
}
</style>
