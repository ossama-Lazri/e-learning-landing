<script>
    import learning from '../assets/learning.jpeg'
    import best1 from '../assets/best1.jpg'
    import best2 from '../assets/best2.jpg'
    import best3 from '../assets/best3.jpg'
    import best4 from '../assets/best4.jpg'
    import best5 from '../assets/best5.jpg'
    import cta from '../assets/cta.png'
    import instructor1 from '../assets/instructor1.jpeg'
    import instructor2 from '../assets/instructor2.jpeg'
    import instructor3 from '../assets/instructor3.jpeg'
    import instructor4 from '../assets/instructor4.jpeg'
    import instructor5 from '../assets/instructor5.jpeg'
</script>

<div class='font-ralewayRegular'>

    <div id="navigation" class="inline-flex flex-col w-full">
        <div id="nav-dark" class="flex justify-between items-center md:px-8 px-5 bg-[#1d2026]">
            <div class="md:flex hidden items-center gap-2">
                <button class="shadow-[0px_2px_0px_0px_#FF6636_inset] text-[#FFF] p-4 text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">Home</button>
                <button class="text-[#8C94A3] p-4 text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">Courses</button>
                <button class="text-[#8C94A3] p-4 text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">About</button>
                <button class="text-[#8C94A3] p-4 text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">Contact</button>
                <button class="text-[#8C94A3] p-4 text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">Become an Instructor</button>
            </div>
            <button class="md:hidden menu1 my-2">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M13.5 18H4M20 12H4M20 6H4" stroke="#fff" stroke-width="2" stroke-linecap="round"/></svg>
            </button>
            <div class="flex items-start md:gap-6 gap-3">
                <select name="" id="" class="text-[#A1A5B3] bg-inherit outline-none md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">
                    <option value="USD">USD</option>
                    <option value="Eu">Eu</option>
                </select>
                <select name="" id="" class="text-[#A1A5B3] bg-inherit outline-none md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">
                    <option value="English">English</option>
                    <option value="French">French</option>
                </select>
            </div>
        </div>
        <div id="nav-light" class="flex justify-between items-center shadow-[0px_-1px_0px_0px_#E9EAF0_inset] md:px-8 px-5 md:py-6 py-3 bg-white">
            <div class="flex items-center gap-8 w-full">
                <button class="logo flex items-center md:gap-2 gap-1.5">
                    <div class="flex md:w-10 w-7 md:h-10 h-7 justify-center items-center">
                        <svg width="42" height="40" viewBox="0 0 42 40" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.25 15L21 5L39.75 15L21 25L2.25 15Z" stroke="#FF6636" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/><path d="M30.375 37.5V20L21 15" stroke="#FF6636" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/><path d="M35.375 17.3333V25.8521C35.3755 26.1218 35.2884 26.3843 35.1266 26.6001C34.074 28.0008 29.6333 33.1249 21 33.1249C12.3667 33.1249 7.92597 28.0008 6.87336 26.6001C6.71165 26.3843 6.62449 26.1218 6.625 25.8521V17.3333" stroke="#FF6636" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </div>
                    <span class="text-[#1D2026] md:text-[2rem] text-lg font-ralewaySemiBold leading-[124%] tracking-[-0.06rem]">E-tutor</span>
                </button>
                <select name="" id="" class="max-w-[7rem] w-full h-10 md:flex hidden border border-[#E9EAF0] px-4 border-solid bg-white outline-none text-[#4E5566] leading-6 text-sm">
                    <option value="">Browse</option>
                    <option value="">Deeple</option>
                </select>
                <div class="md:flex hidden relative max-w-md">
                    <input type="text" class="w-full outline-none h-10 border border-[#E9EAF0] pl-[3.37rem] pr-4 text-sm border-solid placeholder:text-[#8C94A3] text-[#4E5566] leading-6" placeholder="What do you want learn...">
                    <button class="absolute top-1/2 -translate-y-1/2 left-[1.12rem]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M10.875 18.75C15.2242 18.75 18.75 15.2242 18.75 10.875C18.75 6.52576 15.2242 3 10.875 3C6.52576 3 3 6.52576 3 10.875C3 15.2242 6.52576 18.75 10.875 18.75Z" stroke="#1D2026" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M16.4431 16.4438L20.9994 21.0001" stroke="#1D2026" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                </div>
            </div>
            <div class="md:flex hidden items-center gap-6">
                <button>
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M5.26904 9.75C5.2678 8.86051 5.44262 7.97957 5.78343 7.15796C6.12424 6.33635 6.6243 5.59031 7.25477 4.96286C7.88525 4.33541 8.63368 3.83895 9.45693 3.5021C10.2802 3.16525 11.1619 2.99467 12.0514 3.00019C15.763 3.02778 18.7317 6.11282 18.7317 9.83474V10.5C18.7317 13.8577 19.4342 15.8062 20.0529 16.8711C20.1196 16.9849 20.1551 17.1142 20.1558 17.2461C20.1565 17.378 20.1224 17.5077 20.0569 17.6222C19.9915 17.7367 19.8971 17.8319 19.7831 17.8982C19.6691 17.9646 19.5397 17.9997 19.4078 18H4.59222C4.46034 17.9997 4.33087 17.9645 4.21689 17.8982C4.1029 17.8318 4.00844 17.7366 3.94301 17.6221C3.87759 17.5076 3.84352 17.3778 3.84425 17.2459C3.84498 17.1141 3.88048 16.9847 3.94716 16.8709C4.56622 15.806 5.26904 13.8575 5.26904 10.5L5.26904 9.75Z" stroke="#1D2026" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 18V18.75C9 19.5456 9.31607 20.3087 9.87868 20.8713C10.4413 21.4339 11.2044 21.75 12 21.75C12.7956 21.75 13.5587 21.4339 14.1213 20.8713C14.6839 20.3087 15 19.5456 15 18.75V18" stroke="#1D2026" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </button>
                <button>
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M12 20.25C12 20.25 2.625 15 2.625 8.625C2.62519 7.49825 3.01561 6.40634 3.72989 5.53492C4.44416 4.6635 5.4382 4.06635 6.54299 3.84501C7.64778 3.62366 8.79514 3.79178 9.78999 4.32078C10.7848 4.84978 11.5658 5.70701 12 6.74672L12 6.74673C12.4342 5.70701 13.2152 4.84979 14.21 4.32078C15.2049 3.79178 16.3522 3.62366 17.457 3.84501C18.5618 4.06635 19.5558 4.6635 20.2701 5.53492C20.9844 6.40634 21.3748 7.49825 21.375 8.625C21.375 15 12 20.25 12 20.25Z" stroke="#1D2026" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </button>
                <button>
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M8.25 20.25C8.25 20.6642 7.91421 21 7.5 21C7.08579 21 6.75 20.6642 6.75 20.25C6.75 19.8358 7.08579 19.5 7.5 19.5C7.91421 19.5 8.25 19.8358 8.25 20.25Z" fill="#1D2026" stroke="#1D2026" stroke-width="1.5"/><path d="M17.25 21.75C18.0784 21.75 18.75 21.0784 18.75 20.25C18.75 19.4216 18.0784 18.75 17.25 18.75C16.4216 18.75 15.75 19.4216 15.75 20.25C15.75 21.0784 16.4216 21.75 17.25 21.75Z" fill="#1D2026"/><path d="M3.96429 6.75H20.7857L18.3108 15.4121C18.2213 15.7255 18.0321 16.0012 17.7718 16.1975C17.5116 16.3938 17.1945 16.5 16.8685 16.5H7.88145C7.55549 16.5 7.23839 16.3938 6.97816 16.1975C6.71792 16.0012 6.52872 15.7255 6.43917 15.4121L3.04827 3.54396C3.0035 3.38725 2.90889 3.24939 2.77878 3.15124C2.64866 3.05309 2.49011 3 2.32713 3H0.75" stroke="#1D2026" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </button>
                <div class="flex items-center gap-3 whitespace-nowrap">
                    <button class="bg-[#FFEEE8] px-6 text-[#FF6636] text-sm font-ralewaySemiBold h-10 tracking-[-0.008rem] capitalize">Create Account</button>
                    <button class="bg-[#FF6636] px-6 text-[#FFF] text-sm font-ralewaySemiBold h-10 tracking-[-0.008rem] capitalize">Sign In</button>
                </div>
            </div>
            <button class="config md:hidden">
                <svg class="fill-[#1D2026]" xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24"><path d="M480-160q-33 0-56.5-23.5T400-240q0-33 23.5-56.5T480-320q33 0 56.5 23.5T560-240q0 33-23.5 56.5T480-160Zm0-240q-33 0-56.5-23.5T400-480q0-33 23.5-56.5T480-560q33 0 56.5 23.5T560-480q0 33-23.5 56.5T480-400Zm0-240q-33 0-56.5-23.5T400-720q0-33 23.5-56.5T480-800q33 0 56.5 23.5T560-720q0 33-23.5 56.5T480-640Z"/></svg>
            </button>
        </div>
    </div>

    <header id="hero" class="bg-header">
        <div class="flex justify-between md:flex-row flex-col md:py-20 py-10 items-center gap-[4.5rem] container mx-auto md:px-0 px-5">
            <div class="flex flex-col items-start md:gap-10 gap-5 max-w-[40.5rem]">
                <h1 class="text-[#1D2026] lg:text-7xl md:text-5xl text-3xl font-ralewaySemiBold md:leading-[4.625rem] md:tracking-[-0.09rem] -tracking-wide">Learn with expert anytime anywhere</h1>
                <p class="text-[#4E5566] lg:text-2xl md:text-xl text-sm leading-8">Our mision is to help people to find the best course online and learn with expert anytime, anywhere.</p>
                <button class="bg-[#FF6636] md:px-8 px-4 md:py-2 text-[#FFF] lg:text-lg font-ralewaySemiBold leading-[3.5rem] tracking-[-0.01125rem] capitalize">Create Account</button>
            </div>
            <svg class="w-full h-full" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" height="548" viewBox="0 0 900 548" fill="none"><path d="M69.7288 0L900 0V548H0L69.7288 0Z" fill="url(#pattern0)"/><defs><pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1"><use xlink:href="#image0_2132_64236" transform="matrix(0.000244141 0 0 0.000401112 0 0.00702555)"/></pattern><image id="image0_2132_64236" height="2731" xlink:href="{learning}"></image></defs></svg>
        </div>
    </header>

    <section id="category" class="container mx-auto flex flex-col md:gap-10 gap-5 md:py-20 py-10 md:px-0 px-5">
        <h1 class="text-[#1D2026] md:text-[2.5rem] text-xl font-ralewaySemiBold text-center leading-[3rem] tracking-[-0.025rem]">Browse top category</h1>
        <div class="grid lg:grid-cols-4 sm:grid-cols-2 md:gap-6 gap-3">
            <div class="item flex items-center md:gap-5 gap-2.5 md:p-5 p-2.5 bg-[#EBEBFF] w-full hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <span class="md:p-4 p-2 bg-white">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32" fill="none"><path opacity="0.2" d="M25 6H7C6.86868 6 6.73864 6.02586 6.61732 6.07612C6.49599 6.12637 6.38575 6.20003 6.29289 6.29289C6.20003 6.38575 6.12637 6.49599 6.07612 6.61732C6.02586 6.73864 6 6.86868 6 7V25C6 25.1313 6.02586 25.2614 6.07612 25.3827C6.12637 25.504 6.20003 25.6143 6.29289 25.7071C6.38575 25.8 6.49599 25.8736 6.61732 25.9239C6.73864 25.9741 6.86868 26 7 26H25C25.1313 26 25.2614 25.9741 25.3827 25.9239C25.504 25.8736 25.6143 25.8 25.7071 25.7071C25.8 25.6143 25.8736 25.504 25.9239 25.3827C25.9741 25.2614 26 25.1313 26 25V7C26 6.86868 25.9741 6.73864 25.9239 6.61732C25.8736 6.49599 25.8 6.38575 25.7071 6.29289C25.6143 6.20003 25.504 6.12637 25.3827 6.07612C25.2614 6.02586 25.1313 6 25 6ZM19.5 19.5H12.5V12.5H19.5V19.5Z" fill="#564FFD"/><path d="M19.5 12.5H12.5V19.5H19.5V12.5Z" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M25 6H7C6.44772 6 6 6.44772 6 7V25C6 25.5523 6.44772 26 7 26H25C25.5523 26 26 25.5523 26 25V7C26 6.44772 25.5523 6 25 6Z" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M26 13H29" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M26 19H29" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M3 13H6" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M3 19H6" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M19 26V29" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M13 26V29" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M19 3V6" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M13 3V6" stroke="#564FFD" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </span>
                <div class="flex flex-col items-start md:gap-2">
                    <h3 class="text-[#1D2026] md:text-base text-sm font-ralewayMedium leading-[1.375rem]">Label</h3>
                    <span class="text-[#6E7485] md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">63,476 Courses</span>
                </div>
            </div>
            <div class="item flex items-center md:gap-5 gap-2.5 md:p-5 p-2.5 bg-[#E1F7E3] w-full hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <span class="md:p-4 p-2 bg-white">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32" fill="none"><path opacity="0.2" d="M25 19.1077L20.4004 23.7073C20.2783 23.8294 20.1266 23.9178 19.9602 23.9639C19.7938 24.01 19.6182 24.0122 19.4507 23.9703L12.2061 22.1592C12.0702 22.1252 11.943 22.0631 11.8326 21.9768L5 16.6339L9.0718 8.9737L15.4868 7.1035C15.716 7.0367 15.9614 7.05406 16.1789 7.15246L20.5 9.10766H17.9142C17.7829 9.10766 17.6529 9.13353 17.5315 9.18379C17.4102 9.23404 17.3 9.3077 17.2071 9.40056L12.3153 14.2924C12.214 14.3937 12.1356 14.5156 12.0855 14.6498C12.0354 14.784 12.0148 14.9274 12.0249 15.0704C12.0351 15.2133 12.0758 15.3523 12.1444 15.4781C12.213 15.6039 12.3078 15.7135 12.4224 15.7995L13.1 16.3077C13.7924 16.827 14.6345 17.1077 15.5 17.1077C16.3655 17.1077 17.2076 16.827 17.9 16.3077L19.5 15.1077L25 19.1077Z" fill="#23BD33"/><path d="M30.0897 15.2231L27 16.7679L23 9.10768L26.1212 7.5471C26.3557 7.42986 26.6268 7.40939 26.8763 7.4901C27.1257 7.57082 27.3335 7.74626 27.4548 7.97866L30.5289 13.8658C30.5904 13.9835 30.6278 14.1123 30.639 14.2446C30.6501 14.377 30.6348 14.5102 30.5939 14.6365C30.553 14.7629 30.4874 14.8798 30.4008 14.9805C30.3143 15.0812 30.2085 15.1637 30.0897 15.2231V15.2231Z" stroke="#23BD33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M5.00004 16.634L1.91033 15.0891C1.79155 15.0297 1.68579 14.9473 1.59922 14.8466C1.51265 14.7459 1.447 14.6289 1.40612 14.5026C1.36523 14.3762 1.34992 14.243 1.36108 14.1107C1.37224 13.9783 1.40965 13.8495 1.47112 13.7318L4.54523 7.84469C4.66658 7.6123 4.87435 7.43685 5.12378 7.35613C5.37322 7.27541 5.64438 7.29588 5.87887 7.41313L9.00004 8.97371L5.00004 16.634Z" stroke="#23BD33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M27 16.7679L25 19.1077L20.4004 23.7073C20.2783 23.8294 20.1266 23.9178 19.9602 23.9639C19.7938 24.01 19.6182 24.0123 19.4507 23.9704L12.2061 22.1592C12.0702 22.1252 11.943 22.0631 11.8326 21.9768L5 16.634" stroke="#23BD33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M25 19.1077L19.5 15.1077L17.9 16.3077C17.2076 16.827 16.3655 17.1077 15.5 17.1077C14.6345 17.1077 13.7924 16.827 13.1 16.3077L12.4224 15.7995C12.3078 15.7136 12.213 15.604 12.1444 15.4782C12.0758 15.3524 12.0351 15.2133 12.0249 15.0704C12.0148 14.9275 12.0354 14.7841 12.0855 14.6499C12.1356 14.5156 12.214 14.3937 12.3153 14.2924L17.2071 9.40062C17.3 9.30776 17.4102 9.2341 17.5315 9.18385C17.6528 9.13359 17.7829 9.10773 17.9142 9.10773H23" stroke="#23BD33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M9.07166 8.97369L15.4867 7.1035C15.7158 7.0367 15.9613 7.05406 16.1788 7.15246L20.4999 9.10767" stroke="#23BD33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 26.6077L10.2326 25.6658C10.0797 25.6276 9.938 25.5538 9.81907 25.4504L7 23" stroke="#23BD33" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </span>
                <div class="flex flex-col items-start md:gap-2">
                    <h3 class="text-[#1D2026] md:text-base text-sm font-ralewayMedium leading-[1.375rem]">Business</h3>
                    <span class="text-[#6E7485] md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">52,822 Courses</span>
                </div>
            </div>
            <div class="item flex items-center md:gap-5 gap-2.5 md:p-5 p-2.5 bg-[#FFF2E5] w-full hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <span class="md:p-4 p-2 bg-white">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32" fill="none"><path opacity="0.2" d="M2.99933 12.1065H28.9993L29.0001 24C29.0001 24.2652 28.8947 24.5195 28.7072 24.7071C28.5196 24.8946 28.2653 25 28.0001 25H4.00006C3.73484 25 3.48049 24.8946 3.29295 24.7071C3.10542 24.5195 3.00006 24.2652 3.00006 24L2.99933 12.1065Z" fill="#FD8E1F"/><path d="M28 7H4C3.44772 7 3 7.44772 3 8V24C3 24.5523 3.44772 25 4 25H28C28.5523 25 29 24.5523 29 24V8C29 7.44772 28.5523 7 28 7Z" stroke="#FD8E1F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M20.9994 21H24.9994" stroke="#FD8E1F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M14.9993 21H16.9993" stroke="#FD8E1F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M2.99933 12.1065H28.9993" stroke="#FD8E1F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </span>
                <div class="flex flex-col items-start md:gap-2">
                    <h3 class="text-[#1D2026] md:text-base text-sm font-ralewayMedium leading-[1.375rem]">Finance & Accounting</h3>
                    <span class="text-[#6E7485] md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">31,476 Courses</span>
                </div>
            </div>
            <div class="item flex items-center md:gap-5 gap-2.5 md:p-5 p-2.5 bg-[#FFF0F0] w-full hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <span class="md:p-4 p-2 bg-white">
                    <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32" fill="none"><path opacity="0.2" d="M27 13H5V19H27V13Z" fill="#E34444"/><path d="M5 27V5" stroke="#E34444" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M5 7H21V13" stroke="#E34444" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M27 13H5V19H27V13Z" stroke="#E34444" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M17 19V25H5" stroke="#E34444" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
                </span>
                <div class="flex flex-col items-start md:gap-2">
                    <h3 class="text-[#1D2026] font-ralewayMedium md:text-base text-sm leading-[1.375rem]">IT & Software</h3>
                    <span class="text-[#6E7485] md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">99,476 Courses</span>
                </div>
            </div>
        </div>
        <div class="flex items-center gap-3 justify-center md:flex-row flex-col">
            <span class="text-[#4E5566] text-center text-sm leading-[1.375rem] tracking-[-0.00875rem]">We have more category & subcategory.</span>
            <button class="flex items-center gap-2 px-0 py-1 bg-white">
                <span class="text-[#FF6636] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">Browse All</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="24" viewBox="0 0 25 24" fill="none"><path d="M4.25 12H20.75" stroke="#FF6636" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 5.25L20.75 12L14 18.75" stroke="#FF6636" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
            </button>
        </div>
    </section>

    <section id="bestselling" class="bg-[#F5F7FA]">
        <div class="container mx-auto flex flex-col md:gap-10 gap-5 md:py-20 py-10 md:px-0 px-5">
            <h1 class="text-[#1D2026] md:text-[2.5rem] text-xl font-ralewaySemiBold text-center leading-[3rem] tracking-[-0.025rem]">Best selling courses</h1>
            <div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
                <div class="flex flex-col justify-center items-center gap-3.5 pb-3.5 bg-white hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                    <img src="{best1}" alt="">
                    <div class="flex flex-col justify-center w-full items-center gap-2.5">
                        <div class="flex justify-between w-full items-center px-3.5 py-0">
                            <span class="px-1.5 py-1 bg-[#FFEEE8] uppercase text-[#993D20] text-[0.625rem] font-ralewayMedium leading-3">design</span>
                            <span class="text-[#FF6636] font-ralewaySemiBold leading-[1.375rem]">$57</span>
                        </div>
                        <span class="text-[#1D2026] text-sm font-ralewayMedium leading-5 px-3.5 tracking-[-0.00875rem]">Machine Learning A-Z™: Hands-On Python & R In Data...</span>
                    </div>
                    <div class="h-px opacity-70 w-full bg-[#e9eaf0]"></div>
                    <div class="flex justify-between items-center w-full px-3.5 py-0">
                        <span class="flex items-center gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none"><path d="M8.27569 11.9208L11.4279 13.9179C11.8308 14.1732 12.3311 13.7935 12.2115 13.3232L11.3008 9.74052C11.2752 9.64073 11.2782 9.53573 11.3096 9.4376C11.3409 9.33946 11.3994 9.25218 11.4781 9.18577L14.3049 6.83306C14.6763 6.52392 14.4846 5.90751 14.0074 5.87654L10.3159 5.63696C10.2165 5.62986 10.1211 5.59465 10.0409 5.53545C9.96069 5.47625 9.89896 5.39548 9.86289 5.30255L8.48612 1.83549C8.44869 1.73685 8.38215 1.65194 8.29532 1.59201C8.2085 1.53209 8.1055 1.5 8 1.5C7.89451 1.5 7.79151 1.53209 7.70468 1.59201C7.61786 1.65194 7.55131 1.73685 7.51389 1.83549L6.13712 5.30255C6.10104 5.39548 6.03932 5.47625 5.95912 5.53545C5.87892 5.59465 5.78355 5.62986 5.68412 5.63696L1.99263 5.87654C1.51544 5.90751 1.32373 6.52392 1.69515 6.83306L4.52186 9.18577C4.60063 9.25218 4.65907 9.33946 4.69044 9.4376C4.72181 9.53573 4.72485 9.64073 4.6992 9.74052L3.85459 13.063C3.71111 13.6274 4.31143 14.083 4.79495 13.7767L7.72431 11.9208C7.8067 11.8683 7.90234 11.8405 8 11.8405C8.09767 11.8405 8.19331 11.8683 8.27569 11.9208Z" fill="#FD8E1F"/></svg>
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">5.0</span>
                        </span>
                        <span class="flex items-center justify-center gap-1">
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">265.7K</span>
                            <span class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">students</span>
                        </span>
                    </div>
                </div>
                <div class="flex flex-col justify-center items-center gap-3.5 pb-3.5 bg-white hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                    <img src="{best2}" alt="">
                    <div class="flex flex-col justify-center w-full items-center gap-2.5">
                        <div class="flex justify-between w-full items-center px-3.5 py-0">
                            <span class="px-1.5 py-1 bg-[#EBEBFF] uppercase text-[#342F98] text-[0.625rem] font-ralewayMedium leading-3">Developments</span>
                            <span class="text-[#FF6636] font-ralewaySemiBold leading-[1.375rem]">$57</span>
                        </div>
                        <span class="text-[#1D2026] text-sm font-ralewayMedium leading-5 px-3.5 tracking-[-0.00875rem]">The Complete 2021 Web Development Bootcamp</span>
                    </div>
                    <div class="h-px opacity-70 w-full bg-[#e9eaf0]"></div>
                    <div class="flex justify-between items-center w-full px-3.5 py-0">
                        <span class="flex items-center gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none"><path d="M8.27569 11.9208L11.4279 13.9179C11.8308 14.1732 12.3311 13.7935 12.2115 13.3232L11.3008 9.74052C11.2752 9.64073 11.2782 9.53573 11.3096 9.4376C11.3409 9.33946 11.3994 9.25218 11.4781 9.18577L14.3049 6.83306C14.6763 6.52392 14.4846 5.90751 14.0074 5.87654L10.3159 5.63696C10.2165 5.62986 10.1211 5.59465 10.0409 5.53545C9.96069 5.47625 9.89896 5.39548 9.86289 5.30255L8.48612 1.83549C8.44869 1.73685 8.38215 1.65194 8.29532 1.59201C8.2085 1.53209 8.1055 1.5 8 1.5C7.89451 1.5 7.79151 1.53209 7.70468 1.59201C7.61786 1.65194 7.55131 1.73685 7.51389 1.83549L6.13712 5.30255C6.10104 5.39548 6.03932 5.47625 5.95912 5.53545C5.87892 5.59465 5.78355 5.62986 5.68412 5.63696L1.99263 5.87654C1.51544 5.90751 1.32373 6.52392 1.69515 6.83306L4.52186 9.18577C4.60063 9.25218 4.65907 9.33946 4.69044 9.4376C4.72181 9.53573 4.72485 9.64073 4.6992 9.74052L3.85459 13.063C3.71111 13.6274 4.31143 14.083 4.79495 13.7767L7.72431 11.9208C7.8067 11.8683 7.90234 11.8405 8 11.8405C8.09767 11.8405 8.19331 11.8683 8.27569 11.9208Z" fill="#FD8E1F"/></svg>
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">5.0</span>
                        </span>
                        <span class="flex items-center justify-center gap-1">
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">265.7K</span>
                            <span class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">students</span>
                        </span>
                    </div>
                </div>
                <div class="flex flex-col justify-center items-center gap-3.5 pb-3.5 bg-white hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                    <img src="{best3}" alt="">
                    <div class="flex flex-col justify-center w-full items-center gap-2.5">
                        <div class="flex justify-between w-full items-center px-3.5 py-0">
                            <span class="px-1.5 py-1 bg-[#E1F7E3] uppercase text-[#15711F] text-[0.625rem] font-ralewayMedium leading-3">Business</span>
                            <span class="text-[#FF6636] font-ralewaySemiBold leading-[1.375rem]">$57</span>
                        </div>
                        <span class="text-[#1D2026] text-sm font-ralewayMedium leading-5 px-3.5 tracking-[-0.00875rem]">Learn Python Programming Masterclass</span>
                    </div>
                    <div class="h-px opacity-70 w-full bg-[#e9eaf0]"></div>
                    <div class="flex justify-between items-center w-full px-3.5 py-0">
                        <span class="flex items-center gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none"><path d="M8.27569 11.9208L11.4279 13.9179C11.8308 14.1732 12.3311 13.7935 12.2115 13.3232L11.3008 9.74052C11.2752 9.64073 11.2782 9.53573 11.3096 9.4376C11.3409 9.33946 11.3994 9.25218 11.4781 9.18577L14.3049 6.83306C14.6763 6.52392 14.4846 5.90751 14.0074 5.87654L10.3159 5.63696C10.2165 5.62986 10.1211 5.59465 10.0409 5.53545C9.96069 5.47625 9.89896 5.39548 9.86289 5.30255L8.48612 1.83549C8.44869 1.73685 8.38215 1.65194 8.29532 1.59201C8.2085 1.53209 8.1055 1.5 8 1.5C7.89451 1.5 7.79151 1.53209 7.70468 1.59201C7.61786 1.65194 7.55131 1.73685 7.51389 1.83549L6.13712 5.30255C6.10104 5.39548 6.03932 5.47625 5.95912 5.53545C5.87892 5.59465 5.78355 5.62986 5.68412 5.63696L1.99263 5.87654C1.51544 5.90751 1.32373 6.52392 1.69515 6.83306L4.52186 9.18577C4.60063 9.25218 4.65907 9.33946 4.69044 9.4376C4.72181 9.53573 4.72485 9.64073 4.6992 9.74052L3.85459 13.063C3.71111 13.6274 4.31143 14.083 4.79495 13.7767L7.72431 11.9208C7.8067 11.8683 7.90234 11.8405 8 11.8405C8.09767 11.8405 8.19331 11.8683 8.27569 11.9208Z" fill="#FD8E1F"/></svg>
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">5.0</span>
                        </span>
                        <span class="flex items-center justify-center gap-1">
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">265.7K</span>
                            <span class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">students</span>
                        </span>
                    </div>
                </div>
                <div class="flex flex-col justify-center items-center gap-3.5 pb-3.5 bg-white hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                    <img src="{best4}" alt="">
                    <div class="flex flex-col justify-center w-full items-center gap-2.5">
                        <div class="flex justify-between w-full items-center px-3.5 py-0">
                            <span class="px-1.5 py-1 bg-[#EBEBFF] uppercase text-[#342F98] text-[0.625rem] font-ralewayMedium leading-3">Marketing</span>
                            <span class="text-[#FF6636] font-ralewaySemiBold leading-[1.375rem]">$57</span>
                        </div>
                        <span class="text-[#1D2026] text-sm font-ralewayMedium leading-5 px-3.5 tracking-[-0.00875rem]">The Complete Digital Marketing Course - 12 Courses in 1</span>
                    </div>
                    <div class="h-px opacity-70 w-full bg-[#e9eaf0]"></div>
                    <div class="flex justify-between items-center w-full px-3.5 py-0">
                        <span class="flex items-center gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none"><path d="M8.27569 11.9208L11.4279 13.9179C11.8308 14.1732 12.3311 13.7935 12.2115 13.3232L11.3008 9.74052C11.2752 9.64073 11.2782 9.53573 11.3096 9.4376C11.3409 9.33946 11.3994 9.25218 11.4781 9.18577L14.3049 6.83306C14.6763 6.52392 14.4846 5.90751 14.0074 5.87654L10.3159 5.63696C10.2165 5.62986 10.1211 5.59465 10.0409 5.53545C9.96069 5.47625 9.89896 5.39548 9.86289 5.30255L8.48612 1.83549C8.44869 1.73685 8.38215 1.65194 8.29532 1.59201C8.2085 1.53209 8.1055 1.5 8 1.5C7.89451 1.5 7.79151 1.53209 7.70468 1.59201C7.61786 1.65194 7.55131 1.73685 7.51389 1.83549L6.13712 5.30255C6.10104 5.39548 6.03932 5.47625 5.95912 5.53545C5.87892 5.59465 5.78355 5.62986 5.68412 5.63696L1.99263 5.87654C1.51544 5.90751 1.32373 6.52392 1.69515 6.83306L4.52186 9.18577C4.60063 9.25218 4.65907 9.33946 4.69044 9.4376C4.72181 9.53573 4.72485 9.64073 4.6992 9.74052L3.85459 13.063C3.71111 13.6274 4.31143 14.083 4.79495 13.7767L7.72431 11.9208C7.8067 11.8683 7.90234 11.8405 8 11.8405C8.09767 11.8405 8.19331 11.8683 8.27569 11.9208Z" fill="#FD8E1F"/></svg>
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">5.0</span>
                        </span>
                        <span class="flex items-center justify-center gap-1">
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">265.7K</span>
                            <span class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">students</span>
                        </span>
                    </div>
                </div>
                <div class="flex flex-col justify-center items-center gap-3.5 pb-3.5 bg-white hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                    <img src="{best5}" alt="">
                    <div class="flex flex-col justify-center w-full items-center gap-2.5">
                        <div class="flex justify-between w-full items-center px-3.5 py-0">
                            <span class="px-1.5 py-1 bg-[#FFF0F0] uppercase text-[#882929] text-[0.625rem] font-ralewayMedium leading-3">IT & Software</span>
                            <span class="text-[#FF6636] font-ralewaySemiBold leading-[1.375rem]">$57</span>
                        </div>
                        <span class="text-[#1D2026] text-sm font-ralewayMedium leading-5 px-3.5 tracking-[-0.00875rem]">Reiki Level I, II and Master/Teacher Program</span>
                    </div>
                    <div class="h-px opacity-70 w-full bg-[#e9eaf0]"></div>
                    <div class="flex justify-between items-center w-full px-3.5 py-0">
                        <span class="flex items-center gap-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none"><path d="M8.27569 11.9208L11.4279 13.9179C11.8308 14.1732 12.3311 13.7935 12.2115 13.3232L11.3008 9.74052C11.2752 9.64073 11.2782 9.53573 11.3096 9.4376C11.3409 9.33946 11.3994 9.25218 11.4781 9.18577L14.3049 6.83306C14.6763 6.52392 14.4846 5.90751 14.0074 5.87654L10.3159 5.63696C10.2165 5.62986 10.1211 5.59465 10.0409 5.53545C9.96069 5.47625 9.89896 5.39548 9.86289 5.30255L8.48612 1.83549C8.44869 1.73685 8.38215 1.65194 8.29532 1.59201C8.2085 1.53209 8.1055 1.5 8 1.5C7.89451 1.5 7.79151 1.53209 7.70468 1.59201C7.61786 1.65194 7.55131 1.73685 7.51389 1.83549L6.13712 5.30255C6.10104 5.39548 6.03932 5.47625 5.95912 5.53545C5.87892 5.59465 5.78355 5.62986 5.68412 5.63696L1.99263 5.87654C1.51544 5.90751 1.32373 6.52392 1.69515 6.83306L4.52186 9.18577C4.60063 9.25218 4.65907 9.33946 4.69044 9.4376C4.72181 9.53573 4.72485 9.64073 4.6992 9.74052L3.85459 13.063C3.71111 13.6274 4.31143 14.083 4.79495 13.7767L7.72431 11.9208C7.8067 11.8683 7.90234 11.8405 8 11.8405C8.09767 11.8405 8.19331 11.8683 8.27569 11.9208Z" fill="#FD8E1F"/></svg>
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">4.0</span>
                        </span>
                        <span class="flex items-center justify-center gap-1">
                            <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">265.7K</span>
                            <span class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">students</span>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="cta" class="bg-[#F5F7FA]">
        <div class="container mx-auto flex xl:flex-row flex-col justify-between items-center gap-6 md:py-20 py-10 md:px-0 px-5">
            <div class="relative bg-cta w-full max-w-[35.5rem] overflow-hidden">
                <div class="md:p-10 p-5 flex flex-col items-start md:gap-6 gap-3">
                    <span class="text-[#FFF] md:text-[2rem] font-ralewaySemiBold leading-10 tracking-[-0.02rem]">Become an instructor</span>
                    <p class="md:max-w-[19rem] max-w-[9.5rem] text-[#FFF] md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">Instructors from around the world teach millions of students on Udemy. We provide the tools and skills to teach what you love.</p>
                    <button class="flex justify-center z-[9998] items-center md:gap-3 gap-1.5 shadow-[0px_6px_16px_0px_rgba(0,0,0,0.01)] md:px-6 px-3 bg-white">
                        <span class="text-[#FF6636] font-ralewaySemiBold md:leading-[3rem] leading-9 md:text-base text-sm tracking-[-0.008rem] capitalize">Start teaching</span>
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="25" viewBox="0 0 24 25" fill="none"><path d="M3.75 12.5H20.25" stroke="#FF6636" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M13.5 5.75L20.25 12.5L13.5 19.25" stroke="#FF6636" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                </div>
                <img src="{cta}" class="absolute w-full h-full object-contain md:left-40 left-28 top-10" alt="">
            </div>
            <div class="flex flex-col bg-white sm:items-start items-center sm:justify-start justify-center gap-[1.6875rem] md:p-10 p-5">
                <h1 class="text-[#1D2026] md:text-[2rem] font-ralewaySemiBold leading-10 tracking-[-0.02rem]">Your teaching & earning steps</h1>
                <div class="grid md:grid-cols-2 gap-5">
                    <div class="flex items-center sm:gap-4 gap-2">
                        <span class="md:w-[3.25rem] w-10 md:h-[3.25rem] h-10 flex justify-center items-center bg-[#EBEBFF] rounded-full text-[#564FFD] md:text-2xl text-lg font-ralewaySemiBold leading-[124%]">1</span>
                        <span class="text-[#1D2026] leading-6 md:text-base text-sm">Apply to become instructor</span>
                    </div>
                    <div class="flex items-center sm:gap-4 gap-2">
                        <span class="md:w-[3.25rem] w-10 md:h-[3.25rem] h-10 flex justify-center items-center bg-[#FFF0F0] rounded-full text-[#FF6636] md:text-2xl text-lg font-ralewaySemiBold leading-[124%]">2</span>
                        <span class="text-[#1D2026] leading-6 md:text-base text-sm">Build & edit your profile</span>
                    </div>
                    <div class="flex items-center sm:gap-4 gap-2">
                        <span class="md:w-[3.25rem] w-10 md:h-[3.25rem] h-10 flex justify-center items-center bg-[#FFF0F0] rounded-full text-[#E34444] md:text-2xl text-lg font-ralewaySemiBold leading-[124%]">3</span>
                        <span class="text-[#1D2026] leading-6 md:text-base text-sm">Create your new course</span>
                    </div>
                    <div class="flex items-center sm:gap-4 gap-2">
                        <span class="md:w-[3.25rem] w-10 md:h-[3.25rem] h-10 flex justify-center items-center bg-[#E1F7E3] rounded-full text-[#23BD33] md:text-2xl text-lg font-ralewaySemiBold leading-[124%]">4</span>
                        <span class="text-[#1D2026] leading-6 md:text-base text-sm">Start teaching & earning</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="instructor" class="container mx-auto md:px-0 px-5 flex flex-col md:gap-10 gap-5 md:py-20 py-10">
        <h1 class="text-center text-[#1D2026] md:text-[2.5rem] text-[1.25rem] font-ralewaySemiBold leading-[3rem] tracking-[-0.025rem]">Top instructor of the month</h1>
        <div class="grid xl:grid-cols-5 lg:grid-cols-3 sm:grid-cols-2 md:gap-6 gap-3 ">
            <div class="flex flex-col justify-center items-center gap-3 border border-[#E9EAF0] pb-3 border-solid hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)] bg-white">
                <img src="{instructor1}" class="object-cover" alt="">
                <div class="text-center space-y-2">
                    <h1 class="text-[#1D2026] font-ralewayMedium leading-[1.375rem]">Devon Lane</h1>
                    <h2 class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">Senior Developer</h2>
                </div>
                <span class="h-px bg-[#e9eaf0] w-full"></span>
                <div class="flex justify-between items-center px-4 py-0 w-full">
                    <div class="flex items-center gap-[0.3125rem]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none"><path d="M10.3446 14.901L14.2849 17.3974C14.7886 17.7165 15.4139 17.2419 15.2644 16.654L14.126 12.1756C14.0939 12.0509 14.0977 11.9197 14.137 11.797C14.1762 11.6743 14.2492 11.5652 14.3477 11.4822L17.8811 8.54132C18.3453 8.1549 18.1057 7.38439 17.5092 7.34567L12.8949 7.0462C12.7706 7.03732 12.6514 6.99332 12.5511 6.91931C12.4509 6.84531 12.3737 6.74435 12.3286 6.62819L10.6076 2.29436C10.5609 2.17106 10.4777 2.06492 10.3692 1.99002C10.2606 1.91511 10.1319 1.875 10 1.875C9.86813 1.875 9.73938 1.91511 9.63085 1.99002C9.52232 2.06492 9.43914 2.17106 9.39236 2.29436L7.6714 6.62819C7.62631 6.74435 7.54914 6.84531 7.4489 6.91931C7.34865 6.99332 7.22944 7.03732 7.10515 7.0462L2.49078 7.34567C1.89429 7.38439 1.65466 8.1549 2.11894 8.54132L5.65232 11.4822C5.75079 11.5652 5.82383 11.6743 5.86305 11.797C5.90226 11.9197 5.90606 12.0509 5.874 12.1756L4.81824 16.3288C4.63889 17.0343 5.38929 17.6038 5.99369 17.2209L9.65539 14.901C9.75837 14.8354 9.87792 14.8006 10 14.8006C10.1221 14.8006 10.2416 14.8354 10.3446 14.901Z" fill="#FD8E1F"/></svg>
                        <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">4.6</span>
                    </div>
                    <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">854 <span class="text-[#8C94A3] text-sm leading-[1.375rem]">students</span></span>
                </div>
            </div>
            <div class="flex flex-col justify-center items-center gap-3 border border-[#E9EAF0] pb-3 border-solid hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)] bg-white">
                <img src="{instructor2}" class="object-cover" alt="">
                <div class="text-center space-y-2">
                    <h1 class="text-[#1D2026] font-ralewayMedium leading-[1.375rem]">Darrell Steward</h1>
                    <h2 class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">Digital Product Designer</h2>
                </div>
                <span class="h-px bg-[#e9eaf0] w-full"></span>
                <div class="flex justify-between items-center px-4 py-0 w-full">
                    <div class="flex items-center gap-[0.3125rem]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none"><path d="M10.3446 14.901L14.2849 17.3974C14.7886 17.7165 15.4139 17.2419 15.2644 16.654L14.126 12.1756C14.0939 12.0509 14.0977 11.9197 14.137 11.797C14.1762 11.6743 14.2492 11.5652 14.3477 11.4822L17.8811 8.54132C18.3453 8.1549 18.1057 7.38439 17.5092 7.34567L12.8949 7.0462C12.7706 7.03732 12.6514 6.99332 12.5511 6.91931C12.4509 6.84531 12.3737 6.74435 12.3286 6.62819L10.6076 2.29436C10.5609 2.17106 10.4777 2.06492 10.3692 1.99002C10.2606 1.91511 10.1319 1.875 10 1.875C9.86813 1.875 9.73938 1.91511 9.63085 1.99002C9.52232 2.06492 9.43914 2.17106 9.39236 2.29436L7.6714 6.62819C7.62631 6.74435 7.54914 6.84531 7.4489 6.91931C7.34865 6.99332 7.22944 7.03732 7.10515 7.0462L2.49078 7.34567C1.89429 7.38439 1.65466 8.1549 2.11894 8.54132L5.65232 11.4822C5.75079 11.5652 5.82383 11.6743 5.86305 11.797C5.90226 11.9197 5.90606 12.0509 5.874 12.1756L4.81824 16.3288C4.63889 17.0343 5.38929 17.6038 5.99369 17.2209L9.65539 14.901C9.75837 14.8354 9.87792 14.8006 10 14.8006C10.1221 14.8006 10.2416 14.8354 10.3446 14.901Z" fill="#FD8E1F"/></svg>
                        <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">4.9</span>
                    </div>
                    <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">451,444 <span class="text-[#8C94A3] text-sm leading-[1.375rem]">students</span></span>
                </div>
            </div>
            <div class="flex flex-col justify-center items-center gap-3 border border-[#E9EAF0] pb-3 border-solid hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)] bg-white">
                <img src="{instructor3}" class="object-cover" alt="">
                <div class="text-center space-y-2">
                    <h1 class="text-[#1D2026] font-ralewayMedium leading-[1.375rem]">Jane Cooper</h1>
                    <h2 class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">UI/UX Designer</h2>
                </div>
                <span class="h-px bg-[#e9eaf0] w-full"></span>
                <div class="flex justify-between items-center px-4 py-0 w-full">
                    <div class="flex items-center gap-[0.3125rem]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none"><path d="M10.3446 14.901L14.2849 17.3974C14.7886 17.7165 15.4139 17.2419 15.2644 16.654L14.126 12.1756C14.0939 12.0509 14.0977 11.9197 14.137 11.797C14.1762 11.6743 14.2492 11.5652 14.3477 11.4822L17.8811 8.54132C18.3453 8.1549 18.1057 7.38439 17.5092 7.34567L12.8949 7.0462C12.7706 7.03732 12.6514 6.99332 12.5511 6.91931C12.4509 6.84531 12.3737 6.74435 12.3286 6.62819L10.6076 2.29436C10.5609 2.17106 10.4777 2.06492 10.3692 1.99002C10.2606 1.91511 10.1319 1.875 10 1.875C9.86813 1.875 9.73938 1.91511 9.63085 1.99002C9.52232 2.06492 9.43914 2.17106 9.39236 2.29436L7.6714 6.62819C7.62631 6.74435 7.54914 6.84531 7.4489 6.91931C7.34865 6.99332 7.22944 7.03732 7.10515 7.0462L2.49078 7.34567C1.89429 7.38439 1.65466 8.1549 2.11894 8.54132L5.65232 11.4822C5.75079 11.5652 5.82383 11.6743 5.86305 11.797C5.90226 11.9197 5.90606 12.0509 5.874 12.1756L4.81824 16.3288C4.63889 17.0343 5.38929 17.6038 5.99369 17.2209L9.65539 14.901C9.75837 14.8354 9.87792 14.8006 10 14.8006C10.1221 14.8006 10.2416 14.8354 10.3446 14.901Z" fill="#FD8E1F"/></svg>
                        <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">4.8</span>
                    </div>
                    <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">658,644 <span class="text-[#8C94A3] text-sm leading-[1.375rem]">students</span></span>
                </div>
            </div>
            <div class="flex flex-col justify-center items-center gap-3 border border-[#E9EAF0] pb-3 border-solid hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)] bg-white">
                <img src="{instructor4}" class="object-cover" alt="">
                <div class="text-center space-y-2">
                    <h1 class="text-[#1D2026] font-ralewayMedium leading-[1.375rem]">Albert Flores</h1>
                    <h2 class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">Adobe Instructor</h2>
                </div>
                <span class="h-px bg-[#e9eaf0] w-full"></span>
                <div class="flex justify-between items-center px-4 py-0 w-full">
                    <div class="flex items-center gap-[0.3125rem]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none"><path d="M10.3446 14.901L14.2849 17.3974C14.7886 17.7165 15.4139 17.2419 15.2644 16.654L14.126 12.1756C14.0939 12.0509 14.0977 11.9197 14.137 11.797C14.1762 11.6743 14.2492 11.5652 14.3477 11.4822L17.8811 8.54132C18.3453 8.1549 18.1057 7.38439 17.5092 7.34567L12.8949 7.0462C12.7706 7.03732 12.6514 6.99332 12.5511 6.91931C12.4509 6.84531 12.3737 6.74435 12.3286 6.62819L10.6076 2.29436C10.5609 2.17106 10.4777 2.06492 10.3692 1.99002C10.2606 1.91511 10.1319 1.875 10 1.875C9.86813 1.875 9.73938 1.91511 9.63085 1.99002C9.52232 2.06492 9.43914 2.17106 9.39236 2.29436L7.6714 6.62819C7.62631 6.74435 7.54914 6.84531 7.4489 6.91931C7.34865 6.99332 7.22944 7.03732 7.10515 7.0462L2.49078 7.34567C1.89429 7.38439 1.65466 8.1549 2.11894 8.54132L5.65232 11.4822C5.75079 11.5652 5.82383 11.6743 5.86305 11.797C5.90226 11.9197 5.90606 12.0509 5.874 12.1756L4.81824 16.3288C4.63889 17.0343 5.38929 17.6038 5.99369 17.2209L9.65539 14.901C9.75837 14.8354 9.87792 14.8006 10 14.8006C10.1221 14.8006 10.2416 14.8354 10.3446 14.901Z" fill="#FD8E1F"/></svg>
                        <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">4.7</span>
                    </div>
                    <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">511,123 <span class="text-[#8C94A3] text-sm leading-[1.375rem]">students</span></span>
                </div>
            </div>
            <div class="flex flex-col justify-center items-center gap-3 border border-[#E9EAF0] pb-3 border-solid hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)] bg-white">
                <img src="{instructor5}" class="object-cover" alt="">
                <div class="text-center space-y-2">
                    <h1 class="text-[#1D2026] font-ralewayMedium leading-[1.375rem]">Kathryn Murphy</h1>
                    <h2 class="text-[#8C94A3] text-sm leading-[1.375rem] tracking-[-0.00875rem]">Lead Developer</h2>
                </div>
                <span class="h-px bg-[#e9eaf0] w-full"></span>
                <div class="flex justify-between items-center px-4 py-0 w-full">
                    <div class="flex items-center gap-[0.3125rem]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none"><path d="M10.3446 14.901L14.2849 17.3974C14.7886 17.7165 15.4139 17.2419 15.2644 16.654L14.126 12.1756C14.0939 12.0509 14.0977 11.9197 14.137 11.797C14.1762 11.6743 14.2492 11.5652 14.3477 11.4822L17.8811 8.54132C18.3453 8.1549 18.1057 7.38439 17.5092 7.34567L12.8949 7.0462C12.7706 7.03732 12.6514 6.99332 12.5511 6.91931C12.4509 6.84531 12.3737 6.74435 12.3286 6.62819L10.6076 2.29436C10.5609 2.17106 10.4777 2.06492 10.3692 1.99002C10.2606 1.91511 10.1319 1.875 10 1.875C9.86813 1.875 9.73938 1.91511 9.63085 1.99002C9.52232 2.06492 9.43914 2.17106 9.39236 2.29436L7.6714 6.62819C7.62631 6.74435 7.54914 6.84531 7.4489 6.91931C7.34865 6.99332 7.22944 7.03732 7.10515 7.0462L2.49078 7.34567C1.89429 7.38439 1.65466 8.1549 2.11894 8.54132L5.65232 11.4822C5.75079 11.5652 5.82383 11.6743 5.86305 11.797C5.90226 11.9197 5.90606 12.0509 5.874 12.1756L4.81824 16.3288C4.63889 17.0343 5.38929 17.6038 5.99369 17.2209L9.65539 14.901C9.75837 14.8354 9.87792 14.8006 10 14.8006C10.1221 14.8006 10.2416 14.8354 10.3446 14.901Z" fill="#FD8E1F"/></svg>
                        <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">4.2</span>
                    </div>
                    <span class="text-[#4E5566] text-sm font-ralewayMedium leading-5 tracking-[-0.00875rem]">2,711 <span class="text-[#8C94A3] text-sm leading-[1.375rem]">students</span></span>
                </div>
            </div>
        </div>
    </section>

    <section id="companies" class="container mx-auto flex md:flex-row flex-col justify-between flex-wrap items-center w-full gap-6 md:py-20 py-10 md:px-0 px-5">
        <div class="md:text-start text-center">
            <h1 class="text-[#1D2026] md:mb-6 mb-3 md:text-[2rem] text-xl font-ralewaySemiBold leading-10 tracking-[-0.02rem]">6.3k trusted companies</h1>
            <p class="text-[#6E7485] max-w-[19.5rem] text-sm leading-[1.375rem] tracking-[-0.00875rem]">Nullam egestas tellus at enim ornare tristique. Class aptent taciti sociosqu ad litora torquent per conubia nostra.</p>
        </div>
        <div class="grid xl:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <svg width="100" height="100" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M13.7503 61.7705C12.246 62.0346 10.7152 62.1138 9.13174 62.3248L4.30186 48.1786V62.9319C2.79756 63.0902 1.4252 63.3013 0 63.5125V36.4868H4.01172L9.50117 51.8209V36.4868H13.7503V61.7705ZM22.0639 46.3839C23.7003 46.3839 26.2075 46.3047 27.7118 46.3047V50.5274C25.8379 50.5274 23.6475 50.5274 22.0639 50.6066V56.888C24.5448 56.7297 27.0257 56.5184 29.5328 56.4392V60.5034L17.841 61.4273V36.4868H29.5328V40.7096H22.0639V46.3839ZM45.2361 40.7097H40.8551V60.1343C39.4299 60.1343 38.0047 60.1343 36.6325 60.187V40.7097H32.2515V36.4868H45.2363L45.2361 40.7097ZM52.098 46.0937H57.878V50.3163H52.098V59.8968H47.9542V36.4868H59.7519V40.7096H52.098V46.0937ZM66.6138 56.2018C69.0155 56.2544 71.4435 56.4395 73.7925 56.5712V60.7413C70.0185 60.5036 66.2443 60.2664 62.3911 60.187V36.4868H66.6138V56.2018ZM77.3554 61.0316C78.7014 61.1109 80.1266 61.1901 81.4989 61.3482V36.4868H77.3554V61.0316ZM100 36.4868L94.6423 49.3399L100 63.5125C98.4163 63.3013 96.8328 63.011 95.2492 62.747L92.2143 54.9351L89.1267 62.1138C87.5956 61.8497 86.1177 61.7705 84.5872 61.5593L90.0239 49.1814L85.1148 36.4868H89.6541L92.4253 43.5863L95.3813 36.4868H100Z" fill="#D81F26"/></svg>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <div class="flex w-[6.25rem] h-[6.25rem] justify-center items-center">
                    <svg width="100" height="24" viewBox="0 0 100 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M28.4069 1.5026C29.7818 1.87297 30.8625 2.95354 31.2278 4.32347C31.8925 6.80949 31.8925 11.9998 31.8925 11.9998C31.8925 11.9998 31.8925 17.1901 31.2278 19.6761C30.8574 21.051 29.7769 22.1317 28.4069 22.497C25.9209 23.1617 15.9463 23.1617 15.9463 23.1617C15.9463 23.1617 5.97672 23.1617 3.48558 22.497C2.11067 22.1266 1.02997 21.046 0.664706 19.6761C0 17.1901 0 11.9997 0 11.9997C0 11.9997 0 6.80949 0.664706 4.32347C1.03508 2.94856 2.11578 1.86786 3.48558 1.5026C5.97672 0.837891 15.9463 0.837891 15.9463 0.837891C15.9463 0.837891 25.9209 0.837891 28.4069 1.5026ZM21.0452 11.9998L12.7601 16.7842V7.21545L21.0452 11.9998Z" fill="#FF0000"/><path fill-rule="evenodd" clip-rule="evenodd" d="M46.2914 21.1466C45.6623 20.7205 45.2107 20.0609 44.9469 19.163C44.683 18.2649 44.546 17.0726 44.546 15.5809V13.5515C44.546 12.0447 44.6982 10.8373 45.0027 9.92384C45.3071 9.01069 45.7841 8.34612 46.4283 7.92999C47.0727 7.51399 47.92 7.30095 48.9702 7.30095C50.0053 7.30095 50.8323 7.51399 51.4562 7.94022C52.0803 8.36631 52.5369 9.03101 52.8261 9.93407C53.1153 10.8373 53.2575 12.0447 53.2575 13.5464V15.5759C53.2575 17.0675 53.1153 18.2649 52.8362 19.168C52.5572 20.071 52.1007 20.7357 51.4664 21.1517C50.8373 21.5677 49.9798 21.781 48.8991 21.781C47.7931 21.7859 46.9205 21.5728 46.2914 21.1466V21.1466ZM49.8276 18.9549C50.0001 18.4983 50.0915 17.7524 50.0915 16.7226V12.3644C50.0915 11.3597 50.0053 10.6292 49.8276 10.1625C49.6552 9.7007 49.3457 9.46733 48.9042 9.46733C48.4781 9.46733 48.1787 9.7007 48.0012 10.1625C47.8286 10.6241 47.7374 11.3597 47.7374 12.3644V16.7226C47.7374 17.7575 47.8185 18.5034 47.986 18.9549C48.1534 19.4115 48.4578 19.6398 48.8993 19.6398C49.3457 19.6398 49.6501 19.4115 49.8276 18.9549V18.9549ZM94.7287 15.6164V16.3218C94.7287 17.2197 94.7541 17.8894 94.81 18.3409C94.8606 18.7875 94.9723 19.1172 95.1397 19.3203C95.3071 19.5231 95.5658 19.6297 95.9158 19.6297C96.3878 19.6297 96.7124 19.4471 96.885 19.0817C97.0575 18.7164 97.1537 18.1076 97.1691 17.2553L99.8834 17.4126C99.8987 17.5343 99.9037 17.7017 99.9037 17.9147C99.9037 19.2086 99.5485 20.1725 98.8433 20.8118C98.1381 21.451 97.1387 21.7707 95.8449 21.7707C94.2924 21.7707 93.2067 21.2836 92.5826 20.3095C91.9585 19.3354 91.6491 17.8336 91.6491 15.7941V13.3537C91.6491 11.2533 91.9738 9.726 92.618 8.75713C93.2624 7.79312 94.3684 7.31104 95.9363 7.31104C97.0169 7.31104 97.8439 7.50901 98.4222 7.90469C99.0006 8.30036 99.4065 8.9142 99.645 9.75144C99.8784 10.5885 100 11.7454 100 13.2167V15.6115H94.7287V15.6164ZM95.1295 9.73112C94.9721 9.92909 94.8657 10.2537 94.8098 10.7002C94.754 11.1467 94.7287 11.8317 94.7287 12.7397V13.7444H97.0321V12.7397C97.0321 11.8417 97.0017 11.1619 96.9407 10.7002C96.8799 10.2385 96.7683 9.90876 96.611 9.72102C96.4536 9.53328 96.2051 9.43692 95.8702 9.43692C95.5354 9.4318 95.2868 9.53328 95.1295 9.73112ZM38.6303 15.3527L35.0485 2.42015H38.1736L39.4269 8.28017C39.7465 9.72613 39.9799 10.9539 40.1321 11.9737H40.2233C40.3299 11.243 40.5633 10.0203 40.9287 8.30036L42.2274 2.41504H45.3527L41.7303 15.3527V21.5576H38.6303V15.3527ZM63.4197 7.57496V21.5525H60.959L60.685 19.8428H60.6191C59.9494 21.1365 58.9448 21.7809 57.6104 21.7809C56.6821 21.7809 55.9971 21.4765 55.5557 20.8676C55.1143 20.2588 54.8962 19.3101 54.8962 18.0163V7.57496H58.0418V17.8387C58.0418 18.4627 58.1077 18.9093 58.2447 19.1731C58.3817 19.4369 58.61 19.5739 58.9296 19.5739C59.2036 19.5739 59.4674 19.4926 59.716 19.3253C59.9646 19.1579 60.1523 18.9447 60.2741 18.686V7.57483L63.4197 7.57496ZM79.5638 7.57496V21.5525H77.1031L76.8291 19.8428H76.7631C76.0935 21.1365 75.0889 21.7809 73.7545 21.7809C72.8262 21.7809 72.1411 21.4765 71.6998 20.8676C71.2584 20.2588 71.0402 19.3101 71.0402 18.0163V7.57496H74.1859V17.8387C74.1859 18.4627 74.2518 18.9093 74.3888 19.1731C74.5257 19.4369 74.7541 19.5739 75.0737 19.5739C75.3477 19.5739 75.6115 19.4926 75.8601 19.3253C76.1087 19.1579 76.2964 18.9447 76.4182 18.686V7.57483L79.5638 7.57496Z" fill="#282828"/><path fill-rule="evenodd" clip-rule="evenodd" d="M71.9738 4.95233H68.8485V21.5529H65.7688V4.95233H62.6436V2.42068H71.9687V4.95233H71.9738ZM89.9798 9.81267C89.7871 8.92994 89.4827 8.29067 89.0565 7.89499C88.6304 7.49918 88.0469 7.30135 87.301 7.30135C86.7228 7.30135 86.1849 7.46365 85.6826 7.79352C85.1803 8.11813 84.7947 8.54947 84.5207 9.08215H84.4954V1.71533H81.4614V21.558H84.059L84.3786 20.2339H84.4447C84.6882 20.7057 85.0534 21.0761 85.5405 21.35C86.0275 21.624 86.5655 21.761 87.159 21.761C88.2245 21.761 89.0057 21.2688 89.5081 20.2896C90.0103 19.3105 90.259 17.7783 90.259 15.693V13.4809C90.2641 11.9182 90.1676 10.6955 89.9798 9.8128V9.81267ZM87.093 15.5154C87.093 16.5352 87.0524 17.3317 86.9662 17.9101C86.885 18.4886 86.743 18.8995 86.5451 19.1431C86.3472 19.3865 86.0834 19.5083 85.7485 19.5083C85.4897 19.5083 85.2514 19.4475 85.0281 19.3257C84.81 19.2039 84.6273 19.0213 84.4903 18.7777V10.8377C84.5969 10.4571 84.7795 10.1476 85.0383 9.90418C85.297 9.66059 85.576 9.53879 85.8804 9.53879C86.2001 9.53879 86.4486 9.66557 86.6212 9.91415C86.7937 10.1629 86.9155 10.5889 86.9864 11.1775C87.0525 11.7711 87.0879 12.6133 87.0879 13.7091V15.5154H87.093Z" fill="#282828"/></svg>
                </div>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <div class="flex w-[6.25rem] h-[6.25rem] justify-center items-center">
                    <svg width="100" height="34" viewBox="0 0 100 34" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12.3154 0.682617H13.2047C16.2919 0.749731 19.3289 1.99135 21.5101 4.18934C20.7047 5.01149 19.8826 5.80008 19.094 6.62223C17.8691 5.51484 16.3926 4.65914 14.7819 4.35712C12.3993 3.85377 9.83222 4.30679 7.83557 5.66585C5.65436 7.09203 4.17785 9.50814 3.85906 12.092C3.50671 14.6424 4.22819 17.327 5.88926 19.3068C7.48322 21.2364 9.91611 22.4444 12.4329 22.5283C14.7819 22.6625 17.2315 21.9411 18.943 20.2968C20.2852 19.139 20.906 17.3773 21.1074 15.6659C18.3221 15.6659 15.5369 15.6827 12.7517 15.6659V12.2095H24.4799C25.0839 15.9176 24.2114 20.0954 21.3926 22.7464C19.5134 24.6256 16.9128 25.733 14.2617 25.9511C11.6946 26.2028 9.04362 25.7162 6.76175 24.4746C4.02685 23.0149 1.84564 20.5484 0.771812 17.6457C-0.234899 14.978 -0.251678 11.9578 0.687919 9.27324C1.54362 6.82357 3.18792 4.65914 5.30201 3.14907C7.33222 1.65577 9.79866 0.833624 12.3154 0.682617Z" fill="#3780FF"/><path d="M79.5973 1.55518H83.1879V25.5149C81.9966 25.5149 80.7886 25.5317 79.5973 25.4981C79.6141 17.5283 79.5973 9.54175 79.5973 1.55518V1.55518Z" fill="#38B137"/><path d="M32.4665 9.86075C34.6812 9.44129 37.0806 9.91109 38.9094 11.2366C40.5705 12.4111 41.7282 14.2567 42.0806 16.2702C42.5336 18.6024 41.9631 21.1527 40.453 22.9983C38.8255 25.0621 36.1577 26.1695 33.5571 26.0017C31.1745 25.8675 28.8591 24.6762 27.4497 22.7299C25.8557 20.5822 25.4698 17.6292 26.3423 15.1124C27.2148 12.4111 29.6812 10.3473 32.4665 9.86075V9.86075ZM32.9698 13.0487C32.0638 13.2836 31.2248 13.8037 30.6208 14.542C28.9933 16.4883 29.094 19.6594 30.8893 21.4715C31.9128 22.5118 33.4564 22.9983 34.8826 22.7131C36.2081 22.4782 37.3658 21.589 38.0034 20.4145C39.1108 18.4178 38.792 15.6661 37.0973 14.1057C36.0067 13.099 34.4128 12.6795 32.9698 13.0487Z" fill="#FA3913"/><path d="M50.2517 9.86052C52.7852 9.37395 55.5537 10.0786 57.4497 11.8572C60.5369 14.6256 60.8725 19.8102 58.2383 22.9981C56.6443 25.0115 54.0604 26.1189 51.5101 26.0014C49.0772 25.9343 46.6779 24.7263 45.2349 22.7296C43.6074 20.5316 43.2551 17.5115 44.1779 14.9444C45.1007 12.327 47.5168 10.3303 50.2517 9.86052V9.86052ZM50.755 13.0484C49.849 13.2833 49.0101 13.8035 48.4061 14.5249C46.7953 16.4377 46.8624 19.5585 48.5906 21.3874C49.6141 22.478 51.2081 23.0149 52.6846 22.7129C53.9933 22.4612 55.1678 21.5887 55.8054 20.4142C56.896 18.4008 56.5772 15.6491 54.8658 14.0887C53.7752 13.082 52.1812 12.6793 50.755 13.0484Z" fill="#FCBD06"/><path d="M65.3355 10.8332C67.265 9.62517 69.8322 9.2896 71.9127 10.3299C72.5671 10.6151 73.104 11.1017 73.6241 11.5883C73.6409 11.1352 73.6241 10.6654 73.6409 10.1956C74.7651 10.2124 75.8892 10.1956 77.0302 10.2124V25.0111C77.0134 27.2426 76.4429 29.6084 74.8322 31.2359C73.0704 33.0312 70.3691 33.5849 67.9362 33.2157C65.3355 32.8298 63.0704 30.9339 62.0637 28.5345C63.0704 28.048 64.1275 27.6621 65.1677 27.209C65.755 28.5849 66.9463 29.7594 68.4395 30.0278C69.9328 30.2963 71.661 29.9272 72.6342 28.6855C73.6744 27.4104 73.6744 25.6654 73.6241 24.105C72.8523 24.86 71.963 25.5312 70.8892 25.7829C68.557 26.4372 65.9899 25.6319 64.1946 24.0547C62.3825 22.4775 61.3087 20.0446 61.4093 17.6285C61.4597 14.8936 63.0033 12.2594 65.3355 10.8332V10.8332ZM68.8087 12.9809C67.7852 13.1487 66.8288 13.7191 66.1744 14.5077C64.5973 16.3869 64.5973 19.3903 66.1912 21.2359C67.0973 22.3265 68.557 22.9305 69.9664 22.7795C71.2919 22.6453 72.5167 21.8064 73.1711 20.6486C74.2785 18.6856 74.0939 16.0178 72.6006 14.3064C71.6778 13.2493 70.2013 12.7292 68.8087 12.9809V12.9809Z" fill="#3780FF"/><path d="M87.5 11.6891C89.5135 9.80995 92.6175 9.17237 95.2014 10.1623C97.6511 11.0851 99.2115 13.4173 100 15.8167C96.3591 17.3267 92.7349 18.82 89.094 20.3301C89.5973 21.2865 90.3692 22.159 91.4094 22.5113C92.8692 23.0314 94.6141 22.8469 95.839 21.8737C96.3256 21.5046 96.7115 21.018 97.0806 20.5482C98.0034 21.169 98.9262 21.773 99.849 22.3938C98.5403 24.3569 96.3423 25.7328 93.9765 25.9509C91.3591 26.2697 88.5739 25.263 86.8792 23.216C84.094 19.9945 84.3624 14.5918 87.5 11.6891V11.6891ZM89.2953 14.7932C88.7249 15.6153 88.49 16.622 88.5067 17.612C90.9396 16.6053 93.3725 15.5985 95.8054 14.5751C95.4027 13.6355 94.4296 13.065 93.4396 12.914C91.8457 12.6287 90.1846 13.4844 89.2953 14.7932V14.7932Z" fill="#FA3913"/></svg>
                </div>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <svg width="100" height="100" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M41.9125 44.0869C40.1069 44.0869 38.0533 44.9239 36.7986 46.5997L36.7994 46.5964L36.7986 46.5973L36.7994 44.35H32.4927V60.0334H36.7986V51.1094C36.7986 49.5033 38.0438 47.7958 40.3497 47.7958C42.1315 47.7958 43.9756 49.0354 43.9756 51.1094V60.0334H48.2822V50.3114C48.2822 46.7041 45.7014 44.0869 41.9125 44.0869ZM78.8909 44.3508L74.9976 55.0338L71.1042 44.3508H66.1846L72.6376 60.0292H77.3568L83.8097 44.3508H78.8909ZM19.6358 49.0754C20.3691 48.0906 21.5374 47.5124 22.9483 47.5124C24.5002 47.5124 25.6776 48.3987 26.2863 49.707L18.7622 52.8286C18.5568 51.2266 18.9667 49.9736 19.6358 49.0754ZM27.9095 55.2116C26.097 56.553 25.0614 56.873 23.4085 56.873C21.921 56.873 20.7564 56.4112 19.9354 55.6013L30.9455 51.0338C30.705 49.3318 30.059 47.8112 29.065 46.655C27.6184 44.975 25.4772 44.0861 22.8701 44.0861C18.1347 44.0861 14.564 47.5795 14.564 52.1936C14.564 56.9274 18.1432 60.3001 23.3448 60.3001C26.2592 60.3001 29.239 58.9189 30.6329 57.3051L27.9095 55.2116ZM14.1535 56.0791H4.36545V39.6597H0V60.0334H14.1535V56.0791ZM91.5428 47.7766C89.1378 47.7766 87.3913 49.5993 87.3913 52.192C87.3913 54.6676 89.2412 56.6074 91.6006 56.6074C94.0065 56.6074 95.7519 54.7346 95.7519 52.192C95.7519 49.7165 93.9028 47.7766 91.5428 47.7766ZM91.5428 60.2979C86.8329 60.2979 83.1424 56.789 83.1424 52.192C83.1424 47.6465 86.8584 44.0861 91.6006 44.0861C96.3105 44.0861 100 47.5948 100 52.192C100 56.7365 96.2848 60.2977 91.5428 60.2977V60.2979ZM58.3855 47.7766C55.9804 47.7766 54.235 49.5993 54.235 52.192C54.235 54.6676 56.084 56.6074 58.444 56.6074C60.8491 56.6074 62.5945 54.7346 62.5945 52.192C62.5945 49.7165 60.7455 47.7766 58.3855 47.7766ZM58.3855 60.2979C53.6756 60.2979 49.9861 56.789 49.9861 52.192C49.9861 47.6465 53.701 44.0861 58.444 44.0861C63.1531 44.0861 66.8434 47.5948 66.8434 52.192C66.8434 56.7365 63.1277 60.2977 58.3855 60.2977" fill="#E60012"/></svg>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <div class="flex w-[6.25rem] h-[6.25rem] justify-center items-center">
                    <svg width="100" height="26" viewBox="0 0 100 26" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M31.9919 20.2836L33.2399 17.3836C34.5879 18.3916 36.3839 18.9156 38.1559 18.9156C39.4639 18.9156 40.2919 18.4116 40.2919 17.6476C40.2719 15.5116 32.4559 17.1836 32.3959 11.8276C32.3759 9.10764 34.7919 7.01164 38.2159 7.01164C40.2519 7.01164 42.2839 7.51564 43.7359 8.66364L42.5679 11.6236C41.2399 10.7756 39.5879 10.1716 38.0159 10.1716C36.9479 10.1716 36.2439 10.6756 36.2439 11.3196C36.2639 13.4156 44.1399 12.2676 44.2199 17.3836C44.2199 20.1636 41.8639 22.1196 38.4799 22.1196C35.9999 22.1156 33.7239 21.5316 31.9919 20.2836V20.2836ZM79.9159 16.3356C79.2919 17.4236 78.1239 18.1676 76.7719 18.1676C74.7759 18.1676 73.1679 16.5556 73.1679 14.5636C73.1679 12.5716 74.7799 10.9596 76.7719 10.9596C78.1199 10.9596 79.2919 11.7036 79.9159 12.7916L83.3599 10.8796C82.0719 8.58364 79.5919 7.01164 76.7719 7.01164C72.5999 7.01164 69.2159 10.3956 69.2159 14.5676C69.2159 18.7396 72.5999 22.1236 76.7719 22.1236C79.6119 22.1236 82.0719 20.5716 83.3599 18.2556L79.9159 16.3356ZM45.9519 0.743652H50.2639V21.8356H45.9519V0.743652ZM85.0519 0.743652V21.8356H89.3639V15.5076L94.4799 21.8356H99.9999L93.4919 14.3196L99.5159 7.30764H94.2359L89.3599 13.1276V0.743652H85.0519Z" fill="black"/><path d="M63.076 16.3758C62.452 17.4038 61.164 18.1678 59.712 18.1678C57.716 18.1678 56.108 16.5558 56.108 14.5638C56.108 12.5718 57.72 10.9598 59.712 10.9598C61.164 10.9598 62.452 11.7638 63.076 12.8118V16.3758ZM63.076 7.31181V9.02381C62.372 7.83581 60.62 7.00781 58.784 7.00781C54.996 7.00781 52.016 10.3518 52.016 14.5438C52.016 18.7358 54.996 22.1198 58.784 22.1198C60.616 22.1198 62.368 21.2958 63.076 20.1038V21.8158H67.388V7.31181H63.076Z" fill="black"/><path fill-rule="evenodd" clip-rule="evenodd" d="M5.34002 16.3558C5.34002 17.8278 4.15202 19.0158 2.68002 19.0158C1.20802 19.0158 0.0200195 17.8238 0.0200195 16.3558C0.0200195 14.8878 1.20802 13.6958 2.68002 13.6958H5.34002V16.3558ZM6.66802 16.3558C6.66802 14.8838 7.85602 13.6958 9.32802 13.6958C10.8 13.6958 11.988 14.8838 11.988 16.3558V23.0038C11.988 24.4758 10.8 25.6638 9.32802 25.6638C7.85602 25.6638 6.66802 24.4758 6.66802 23.0038V16.3558Z" fill="#E01E5A"/><path fill-rule="evenodd" clip-rule="evenodd" d="M9.328 5.67988C7.856 5.67988 6.668 4.49187 6.668 3.01987C6.668 1.54787 7.856 0.359863 9.328 0.359863C10.8 0.359863 11.988 1.54787 11.988 3.01987V5.67988H9.328ZM9.328 7.02788C10.8 7.02788 11.988 8.21588 11.988 9.68789C11.988 11.1599 10.8 12.3479 9.328 12.3479H2.66C1.188 12.3479 0 11.1559 0 9.68789C0 8.21988 1.188 7.02788 2.66 7.02788H9.328Z" fill="#36C5F0"/><path fill-rule="evenodd" clip-rule="evenodd" d="M19.984 9.68789C19.984 8.21588 21.172 7.02788 22.644 7.02788C24.116 7.02788 25.304 8.21588 25.304 9.68789C25.304 11.1599 24.116 12.3479 22.644 12.3479H19.984V9.68789ZM18.656 9.68789C18.656 11.1599 17.4681 12.3479 15.9961 12.3479C14.5241 12.3479 13.3361 11.1599 13.3361 9.68789V3.01987C13.3361 1.54787 14.5241 0.359863 15.9961 0.359863C17.4681 0.359863 18.656 1.54787 18.656 3.01987V9.68789Z" fill="#2EB67D"/><path fill-rule="evenodd" clip-rule="evenodd" d="M15.9961 20.3438C17.468 20.3438 18.656 21.5318 18.656 23.0038C18.656 24.4758 17.468 25.6638 15.9961 25.6638C14.5241 25.6638 13.3361 24.4758 13.3361 23.0038V20.3438H15.9961ZM15.9961 19.0158C14.5241 19.0158 13.3361 17.8278 13.3361 16.3558C13.3361 14.8838 14.5241 13.6958 15.9961 13.6958H22.664C24.136 13.6958 25.324 14.8838 25.324 16.3558C25.324 17.8278 24.136 19.0158 22.664 19.0158H15.9961Z" fill="#ECB22E"/></svg>
                </div>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <svg width="100" height="100" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M97.6607 38.9602C98.4277 38.9198 99.1946 38.9198 99.9615 38.94C97.6607 43.7434 95.4407 48.5872 93.2004 53.4109H91.3235C90.2942 50.989 89.0832 48.6276 88.0135 46.2057C88.7603 46.1855 89.507 46.1855 90.2538 46.2057C90.8996 47.6992 91.6666 49.1322 92.2519 50.6257C94.0481 46.7305 95.9049 42.8554 97.6607 38.9602Z" fill="#FF0000"/><path d="M39.8785 41.019C41.3519 41.0392 42.8454 41.0392 44.3187 41.019C44.2985 42.3309 44.2985 43.6629 44.3187 44.9748C42.8454 44.9546 41.3519 44.9748 39.8584 44.9546C39.8987 43.6428 39.8584 42.3309 39.8785 41.019ZM17.5365 46.6701C20.5639 44.9546 24.9637 45.5399 27.0021 48.5067C28.2534 50.2626 28.6167 52.4827 28.5965 54.5816C25.1252 54.6018 21.6538 54.5816 18.1824 54.6018C18.3438 55.6715 18.808 56.8017 19.797 57.3668C21.2098 58.1943 23.4298 57.9521 24.1362 56.3173C25.5692 56.277 26.9819 56.277 28.4149 56.3173C27.9709 57.9521 26.7801 59.3447 25.2866 60.1116C23.672 60.9997 21.7345 61.1611 19.9383 60.8584C18.0411 60.5556 16.2852 59.486 15.2156 57.8916C14.045 56.1962 13.7422 54.0367 14.0046 52.0387C14.267 49.8388 15.5788 47.76 17.5365 46.6701ZM19.8979 49.1929C18.9089 49.6571 18.4246 50.7268 18.2026 51.7561H24.1362C24.0151 50.969 23.7326 50.1415 23.1271 49.5966C22.2794 48.7691 20.9272 48.7489 19.8979 49.1929ZM64.0773 45.9032C66.4589 45.4794 69.1028 45.9839 70.9394 47.6389C74.0677 50.4241 74.2089 55.8128 71.3027 58.7998C69.0019 61.2015 65.147 61.6455 62.2004 60.2933C59.9197 59.264 58.3657 56.943 58.1033 54.4807C58.0024 53.0478 58.063 51.5745 58.6482 50.2424C59.5363 47.9618 61.6958 46.3068 64.0773 45.9032ZM64.5819 49.1929C63.3306 49.6369 62.7453 50.9892 62.5636 52.2203C62.4224 53.7542 62.4426 55.4899 63.4315 56.7613C64.5012 58.1539 66.8625 58.1136 67.9322 56.7412C68.8202 55.6311 68.9615 54.1174 68.8606 52.745C68.8 51.5341 68.3762 50.2424 67.3671 49.4957C66.5598 48.9507 65.4901 48.87 64.5819 49.1929ZM79.9206 46.7307C81.3939 45.5803 83.4929 45.4592 85.1882 46.1454C86.3992 46.6701 87.3074 47.7398 87.7312 48.9709C88.2156 50.2424 88.0743 51.6148 88.0743 52.9469C88.0743 55.4899 88.0541 58.0328 88.0945 60.5556C86.6212 60.5758 85.1478 60.5556 83.6543 60.5758V51.857C83.6543 51.1103 83.3718 50.303 82.7461 49.8388C81.7975 49.1929 80.4251 49.314 79.6178 50.1213C78.972 50.7672 78.6894 51.6956 78.7096 52.5836V60.5758C77.2565 60.5556 75.7832 60.5758 74.33 60.5556C74.33 55.7522 74.3502 50.9488 74.33 46.1454C75.763 46.1656 77.1758 46.1252 78.6087 46.1656C78.5885 46.8316 78.5885 47.4976 78.5684 48.1636C79.0124 47.6792 79.3756 47.1343 79.9206 46.7307ZM0.0383301 46.1857H4.63994C5.56833 49.2737 6.55727 52.3616 7.42512 55.4697C8.49479 52.4221 9.30209 49.2737 10.3112 46.1857C11.7845 46.1656 13.278 46.1857 14.7514 46.1656C13.056 50.969 11.4011 55.7724 9.72592 60.5758C8.19205 60.5758 6.65818 60.5556 5.12431 60.596C3.36844 55.8128 1.81439 50.9488 0.0383301 46.1857ZM29.6057 46.1656H33.844C33.8238 46.9729 33.844 47.7802 33.8036 48.5875C34.1669 48.1838 34.4293 47.6792 34.8127 47.2958C35.7613 46.2463 37.3154 45.8225 38.6878 46.1857C38.6676 47.4572 38.6676 48.7287 38.6878 49.98C37.5979 49.859 36.387 49.8993 35.4586 50.5653C34.4696 51.2515 34.0256 52.523 34.0458 53.6936C34.0256 55.9944 34.0458 58.275 34.0458 60.5758C32.5725 60.5758 31.079 60.5556 29.6057 60.596C29.6258 55.7724 29.6258 50.969 29.6057 46.1656ZM39.8785 46.1857C41.372 46.1656 42.8454 46.1857 44.3389 46.1656C44.3187 50.969 44.3389 55.7724 44.3389 60.5758C42.8656 60.5556 41.372 60.5758 39.8785 60.5758V46.1857ZM45.5296 46.1656C49.5459 46.1857 53.5623 46.1656 57.5584 46.1857C57.518 47.2958 57.5584 48.3856 57.5382 49.4957C57.3969 49.7782 57.1547 49.98 56.9731 50.2222C54.9145 52.5029 52.8962 54.844 50.7973 57.1044C53.1586 57.1448 55.52 57.1044 57.8813 57.1246V60.596C53.7641 60.5758 49.6469 60.5758 45.5296 60.596V57.2457C47.6892 54.8238 49.8285 52.4221 52.0082 50.0204C52.0688 49.8993 52.3311 49.7782 52.1899 49.6168C49.9698 49.6773 47.7497 49.6168 45.5296 49.6571V46.1656Z" fill="black"/></svg>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <div class="flex w-[6.25rem] h-[6.25rem] justify-center items-center">
                    <svg width="100" height="20" viewBox="0 0 100 20" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M15.919 0.150391H0.0489502V4.01039L1.49895 9.75039L6.04895 10.0104L9.90895 6.15039L17.549 4.51039L15.919 0.150391Z" fill="#00C425"/><path d="M0.0489502 4.01025V19.8802H3.90895L10.369 19.3402L9.91895 13.8702L0.0489502 4.01025V4.01025Z" fill="#3AF23A"/><path d="M3.90637 19.8798H19.7764V16.0198L18.0864 10.8798L13.7664 10.0098L3.90637 19.8798Z" fill="#006446"/><path d="M95.6784 7.98053L92.1884 11.1506L95.6784 14.3407V16.1807H95.5684L90.3884 11.4806V15.9507H88.8884V2.43041H90.3884V10.8806L95.5384 6.19049H95.6784V7.98053V7.98053ZM27.9884 15.9507H35.6484V14.4407H29.5484V2.87042H27.9884V15.9507ZM40.9484 6.20049C38.5984 6.20049 36.4584 8.11054 36.4584 11.1906C36.4584 14.1807 38.4184 16.1607 41.2384 16.1607C42.4984 16.1607 43.6584 15.8407 44.7084 15.0807V13.4707C43.6084 14.3907 42.3884 14.7807 41.2884 14.7807C39.5984 14.7807 38.0984 13.7307 37.9584 11.7706H45.0984C45.1184 11.5806 45.1584 11.1606 45.1584 11.0006C45.1584 7.85053 43.2584 6.20049 40.9484 6.20049V6.20049ZM40.9584 7.57053C42.2884 7.57053 43.6384 8.43054 43.6884 10.4606H37.9484C38.0384 8.89055 39.2484 7.57053 40.9584 7.57053ZM66.1484 6.20049C64.8784 6.20049 63.9584 6.87051 63.4084 7.86053C62.9484 6.80051 62.0984 6.20049 60.7384 6.20049C59.5484 6.20049 58.6684 6.89051 58.1884 7.81053H58.1484L57.9684 6.3905H56.7784V15.9407H58.2984V9.91058C58.2984 8.74055 59.0284 7.65053 60.3484 7.65053C61.6384 7.65053 62.2084 8.41054 62.2084 9.79057V15.9507H63.7284V9.81057C63.7284 8.70055 64.4684 7.65053 65.7684 7.65053C67.0784 7.65053 67.6384 8.41054 67.6384 9.79057V15.9507H69.1584V9.58057C69.1684 7.58052 68.2384 6.20049 66.1484 6.20049V6.20049ZM75.3184 6.20049C73.0384 6.20049 70.9084 8.13054 70.9084 11.1906C70.9084 14.2107 73.0284 16.1607 75.3184 16.1607C76.7484 16.1607 78.0984 15.4907 78.8184 14.1607H78.8384L79.0184 15.9507H80.2584V6.4005H79.0184L78.8384 8.19054H78.8184C78.0984 6.88051 76.7484 6.20049 75.3184 6.20049ZM75.5984 7.62053C77.3984 7.62053 78.7684 9.07056 78.7684 11.1806C78.7684 13.2806 77.4084 14.7407 75.5984 14.7407C73.8284 14.7407 72.4284 13.3107 72.4284 11.2006C72.4284 9.05056 73.8284 7.62053 75.5984 7.62053V7.62053ZM86.7384 6.2905C85.9084 6.2905 84.6484 6.68051 83.9984 7.92053H83.9784L83.8184 6.4005H82.5984V15.9507H84.1184V10.4506C84.1184 8.24054 85.9084 7.55052 87.3784 7.85053V6.3405C87.1784 6.3105 86.9884 6.2905 86.7384 6.2905V6.2905ZM54.8284 6.18049H54.7084L50.7184 10.1606L46.7384 6.18049H46.6184V8.11054L49.6884 11.1806L46.6184 14.2307V16.1807H46.7384L50.6984 12.1806L54.7084 16.1807H54.8284V14.2207L51.7284 11.1506L54.8284 8.03053V6.18049V6.18049ZM95.6784 2.64041V2.43041H97.3384V2.64041H96.6384V4.30045H96.3884V2.63042C96.3784 2.64042 95.6784 2.64041 95.6784 2.64041V2.64041ZM98.1784 2.43041L98.8984 4.01045L99.6184 2.43041H99.9584V4.30045H99.7184V2.73042L98.9984 4.30045H98.7884L98.0784 2.73042V4.30045H97.8384V2.42041H98.1784V2.43041Z" fill="#32323C"/><path d="M19.782 16.0204V0.150391H15.922L9.922 6.15039L19.782 16.0204Z" fill="#008A44"/></svg>
                </div>
            </button>
            <button class="px-[3.125rem] bg-white shadow-[0px_0px_32px_0px_rgba(9,26,68,0.07)] hover:shadow-[0px_12px_32px_0px_rgba(29,32,38,0.10)]">
                <div class="flex w-[6.25rem] h-[6.25rem] justify-center items-center">
                    <svg width="100" height="22" viewBox="0 0 100 22" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M100 9.98294V8.22428H97.8161V5.49023L97.7425 5.51287L95.6913 6.14049L95.6508 6.15278V8.22438H92.4132V7.07032C92.4132 6.53295 92.5333 6.12172 92.7702 5.84748C93.0053 5.57652 93.3417 5.43877 93.7707 5.43877C94.0791 5.43877 94.3984 5.51142 94.7198 5.65468L94.8003 5.69067V3.83856L94.7624 3.82463C94.4626 3.71687 94.0549 3.6626 93.5495 3.6626C92.9125 3.6626 92.3337 3.80122 91.8289 4.07595C91.3239 4.35107 90.9266 4.74382 90.6483 5.24317C90.3709 5.74194 90.2302 6.318 90.2302 6.95549V8.22428H88.7095V9.98294H90.2302V17.3919H92.4132V9.98294H95.6508V14.6912C95.6508 16.6303 96.5655 17.6129 98.3693 17.6129C98.6657 17.6129 98.9777 17.5782 99.2962 17.5102C99.6205 17.4403 99.8413 17.3706 99.9713 17.2961L100 17.2791V15.5041L99.9113 15.5629C99.7928 15.6418 99.6452 15.7063 99.4723 15.7543C99.2985 15.8032 99.1534 15.8276 99.041 15.8276C98.6185 15.8276 98.3058 15.7138 98.1119 15.4891C97.9157 15.2623 97.8162 14.8658 97.8162 14.3111V9.98294H100ZM83.8344 15.8279C83.042 15.8279 82.4173 15.5652 81.9771 15.0477C81.5341 14.5275 81.3097 13.7859 81.3097 12.8437C81.3097 11.8716 81.5341 11.1108 81.9773 10.5814C82.4178 10.0556 83.0365 9.7887 83.8166 9.7887C84.5736 9.7887 85.1761 10.0436 85.6078 10.5467C86.0415 11.0525 86.2617 11.8072 86.2617 12.7906C86.2617 13.7861 86.0547 14.5508 85.6465 15.0624C85.241 15.57 84.6314 15.8279 83.8344 15.8279V15.8279ZM83.9314 8.00343C82.4197 8.00343 81.2191 8.44639 80.363 9.32001C79.5074 10.1937 79.0737 11.4028 79.0737 12.914C79.0737 14.3494 79.4971 15.504 80.3323 16.3451C81.1675 17.1865 82.3041 17.6127 83.7104 17.6127C85.1757 17.6127 86.3525 17.1636 87.2082 16.2778C88.0639 15.3931 88.4973 14.1954 88.4973 12.7195C88.4973 11.2617 88.0906 10.0985 87.288 9.26303C86.485 8.42714 85.3555 8.00343 83.9314 8.00343V8.00343ZM75.5539 8.00343C74.5256 8.00343 73.675 8.26646 73.0253 8.78506C72.3715 9.30676 72.0399 9.99097 72.0399 10.8189C72.0399 11.2493 72.1115 11.6316 72.2524 11.9559C72.3941 12.2812 72.6134 12.5676 72.9047 12.808C73.1939 13.0465 73.6402 13.2962 74.2317 13.5504C74.7289 13.755 75.0997 13.928 75.3352 14.0644C75.5655 14.1981 75.7288 14.3325 75.8211 14.4634C75.9108 14.5914 75.9563 14.7667 75.9563 14.983C75.9563 15.5989 75.495 15.8986 74.546 15.8986C74.1939 15.8986 73.7924 15.8251 73.3525 15.6802C72.9158 15.5375 72.5036 15.3285 72.1304 15.0605L72.0397 14.9955V17.0973L72.073 17.1128C72.3819 17.2554 72.7713 17.3756 73.2304 17.4702C73.6885 17.5649 74.1048 17.6131 74.4663 17.6131C75.5822 17.6131 76.4808 17.3488 77.1364 16.8271C77.7963 16.3018 78.1307 15.6015 78.1307 14.7449C78.1307 14.1269 77.9507 13.597 77.5958 13.1696C77.2434 12.7457 76.6318 12.3566 75.7787 12.0126C75.099 11.7398 74.6636 11.5133 74.4839 11.3395C74.3108 11.1715 74.2229 10.934 74.2229 10.6333C74.2229 10.3667 74.3314 10.1531 74.5542 9.98014C74.7787 9.8063 75.0913 9.71788 75.4832 9.71788C75.847 9.71788 76.2191 9.77535 76.5892 9.88795C76.959 10.0005 77.2839 10.1514 77.555 10.3358L77.6442 10.3968V8.40305L77.61 8.38834C77.3598 8.28106 77.0299 8.18926 76.6293 8.11478C76.2304 8.04077 75.8686 8.00343 75.5539 8.00343V8.00343ZM66.3489 15.8279C65.5567 15.8279 64.9318 15.5652 64.4917 15.0477C64.0486 14.5275 63.8246 13.7861 63.8246 12.8437C63.8246 11.8716 64.0489 11.1108 64.4921 10.5814C64.9323 10.0556 65.5509 9.7887 66.3314 9.7887C67.088 9.7887 67.6906 10.0436 68.1223 10.5467C68.5562 11.0525 68.7763 11.8072 68.7763 12.7906C68.7763 13.7861 68.5692 14.5508 68.1609 15.0624C67.7555 15.57 67.1462 15.8279 66.3489 15.8279V15.8279ZM66.4462 8.00343C64.9341 8.00343 63.7333 8.44639 62.8777 9.32001C62.0222 10.1937 61.5881 11.4028 61.5881 12.914C61.5881 14.35 62.0118 15.504 62.8471 16.3451C63.6823 17.1865 64.8188 17.6127 66.2251 17.6127C67.6902 17.6127 68.8673 17.1636 69.723 16.2778C70.5784 15.3931 71.0121 14.1954 71.0121 12.7195C71.0121 11.2617 70.6052 10.0985 69.8024 9.26303C68.9992 8.42714 67.87 8.00343 66.4462 8.00343V8.00343ZM58.2744 9.81191V8.22428H56.1179V17.3917H58.2744V12.7022C58.2744 11.9048 58.4552 11.2497 58.8119 10.7549C59.1641 10.266 59.6335 10.0182 60.2066 10.0182C60.4008 10.0182 60.6189 10.0503 60.855 10.1136C61.0887 10.1766 61.258 10.245 61.3578 10.317L61.4485 10.3827V8.20861L61.4135 8.19362C61.2127 8.10829 60.9286 8.06525 60.5691 8.06525C60.0272 8.06525 59.5423 8.23937 59.1269 8.5822C58.7623 8.88354 58.4988 9.2967 58.2973 9.81191H58.2744ZM52.2562 8.00343C51.2669 8.00343 50.3844 8.21557 49.6339 8.63376C48.8817 9.05292 48.3001 9.65133 47.9043 10.4123C47.5103 11.1713 47.3103 12.058 47.3103 13.0469C47.3103 13.913 47.5042 14.7079 47.8876 15.4085C48.2712 16.1102 48.814 16.6592 49.5012 17.0399C50.1875 17.4202 50.9806 17.613 51.8588 17.613C52.8836 17.613 53.7586 17.4081 54.4601 17.004L54.4884 16.9878V15.0121L54.3978 15.0783C54.08 15.3098 53.7249 15.4946 53.3428 15.6277C52.9617 15.7607 52.6142 15.8279 52.3095 15.8279C51.4633 15.8279 50.784 15.5632 50.291 15.0412C49.7969 14.5185 49.5463 13.7846 49.5463 12.861C49.5463 11.9317 49.8076 11.1789 50.3225 10.6234C50.8359 10.0696 51.5164 9.7887 52.3451 9.7887C53.0538 9.7887 53.7445 10.0287 54.398 10.5027L54.4884 10.5684V8.48673L54.4592 8.47028C54.2133 8.33262 53.8779 8.21896 53.4616 8.13277C53.047 8.04677 52.6415 8.00343 52.2562 8.00343V8.00343ZM45.8251 8.22438H43.6687V17.3917H45.8251V8.22438V8.22438ZM44.7689 4.31905C44.414 4.31905 44.1045 4.43987 43.8501 4.67929C43.5948 4.91939 43.4652 5.22169 43.4652 5.57845C43.4652 5.92961 43.5932 6.22639 43.8462 6.46011C44.0975 6.69314 44.408 6.81126 44.769 6.81126C45.13 6.81126 45.4416 6.69314 45.696 6.46049C45.9519 6.22639 46.0817 5.9297 46.0817 5.57845C46.0817 5.23417 45.9554 4.93497 45.7065 4.68897C45.4578 4.44345 45.1422 4.31905 44.7689 4.31905ZM39.3885 7.548V17.3917H41.5892V4.59968H38.5433L34.6718 14.1012L30.9147 4.59968H27.7448V17.3916H29.8129V7.54703H29.8839L33.8513 17.3917H35.412L39.3175 7.548H39.3885V7.548Z" fill="#706D6E"/><path d="M10.1445 10.4697H0V0.325195H10.1445V10.4697Z" fill="#F1511B"/><path d="M21.3451 10.4697H11.2008V0.325195H21.3451V10.4697Z" fill="#80CC28"/><path d="M10.1442 21.6741H0V11.5298H10.1442V21.6741Z" fill="#00ADEF"/><path d="M21.3451 21.6741H11.2008V11.5298H21.3451V21.6741Z" fill="#FBBC09"/></svg>
                </div>
            </button>
        </div>
    </section>

    <footer class="inline-flex flex-col justify-center items-center md:gap-20 gap-10 bg-[#1D2026] w-full">
        <div class="shadow-[0px_-1px_0px_0px_rgba(54,59,71,0.50)_inset] md:py-[6.25rem] py-[3.12rem] w-full">
            <div class="flex justify-between flex-wrap items-center md:gap-16 gap-8 container mx-auto lg:px-0 px-5 ">
                <div class="md:max-w-[33.5rem] w-full flex flex-col sm:items-start items-center md:text-start text-center md:justify-start justify-center">
                    <h1 class="text-[#FFF] md:text-[2.5rem] text-[1.25rem] mb-8 font-ralewaySemiBold leading-[3rem] tracking-[-0.025rem]">Start learning with 67.1k students around the world.</h1>
                    <div class="flex flex-wrap gap-4 sm:items-start items-center md:justify-start justify-center">
                        <button class="text-[#FFF] font-ralewaySemiBold sm:leading-[3rem] leading-10 tracking-[-0.008rem] capitalize sm:px-6 px-3 sm:text-base text-sm bg-[#FF6636]">Join the Family</button>
                        <button class="text-[#FFF] font-ralewaySemiBold sm:leading-[3rem] leading-10 tracking-[-0.008rem] capitalize sm:px-6 px-3 sm:text-base text-sm bg-[#ffffff0d]">Browse all courses</button>
                    </div>
                </div>
                <div class="flex flex-wrap gap-6 md:w-fit w-full sm:justify-start justify-center">
                    <button class="flex flex-col items-start md:gap-3 hover:scale-110">
                        <h1 class="text-white md:text-[2.5rem] text-2xl font-ralewaySemiBold md:leading-[3rem] tracking-[-0.025rem]">6.3k</h1>
                        <h2 class="text-[#B7BAC7] font-ralewayMedium md:text-sm text-xs leading-[1.375rem]">Online courses</h2>
                    </button>
                    <button class="flex flex-col items-start md:gap-3 hover:scale-110">
                        <h1 class="text-white md:text-[2.5rem] text-2xl font-ralewaySemiBold md:leading-[3rem] tracking-[-0.025rem]">26k</h1>
                        <h2 class="text-[#B7BAC7] font-ralewayMedium md:text-sm text-xs leading-[1.375rem]">Certified Instructor</h2>
                    </button>
                    <button class="flex flex-col items-start md:gap-3 hover:scale-110">
                        <h1 class="text-white md:text-[2.5rem] text-2xl font-ralewaySemiBold md:leading-[3rem] tracking-[-0.025rem]">99.9%</h1>
                        <h2 class="text-[#B7BAC7] font-ralewayMedium md:text-sm text-xs leading-[1.375rem]">Sucess Rate</h2>
                    </button>
                </div>
            </div>
        </div>
        <div class="flex justify-between sm:text-start text-center sm:items-start items-center sm:flex-row flex-col flex-wrap md:gap-6 gap-12 container mx-auto md:px-0 px-5">
            <div class="flex flex-col sm:items-start items-center sm:justify-start justify-center sm:text-start text-center sm:w-fit w-full">
                <button class="logo flex items-center gap-[0.58rem]">
                    <svg class="md:w-[48px] w-[32px]" width="48" height="46" viewBox="0 0 48 46" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.4375 17.25L24 5.75L45.5625 17.25L24 28.75L2.4375 17.25Z" stroke="#FF6636" stroke-width="3.45" stroke-linecap="round" stroke-linejoin="round"/><path d="M34.7812 43.125V23L24 17.25" stroke="#FF6636" stroke-width="3.45" stroke-linecap="round" stroke-linejoin="round"/><path d="M40.5313 19.9331V29.7298C40.5319 30.0399 40.4316 30.3418 40.2456 30.59C39.0351 32.2007 33.9283 38.0935 24 38.0935C14.0717 38.0935 8.96486 32.2007 7.75437 30.59C7.5684 30.3418 7.46816 30.0399 7.46875 29.7298V19.9331" stroke="#FF6636" stroke-width="3.45" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    <span class="text-[#FFF] md:text-[2.3rem] text-[1.15rem] font-ralewaySemiBold leading-[124%] tracking-[-0.069rem]">E-tutor</span>
                </button>
                <p class="text-[#8C94A3] md:text-sm text-xs leading-[1.375rem] mt-5 mb-[1.62rem] tracking-[-0.00875rem]">Aliquam rhoncus ligula est, non pulvinar elit <br> convallis nec. Donec mattis odio at.</p>
                <div class="flex flex-wrap md:gap-3 gap-1.5">
                    <button class="p-[0.875rem] bg-[#363b4766] hover:shadow-[0px_6px_20px_0px_rgba(204,82,43,0.50)] hover:bg-[#ff6636]">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M11.3575 2.98875H13.0008V0.12675C12.7172 0.08775 11.7423 0 10.6068 0C8.2375 0 6.6145 1.49025 6.6145 4.22925V6.75H4V9.9495H6.6145V18H9.82V9.95025H12.3288L12.727 6.75075H9.81925V4.5465C9.82 3.62175 10.069 2.98875 11.3575 2.98875Z" fill="white"/></svg>
                    </button>
                    <button class="p-[0.875rem] bg-[#363b4766] hover:shadow-[0px_6px_20px_0px_rgba(204,82,43,0.50)] hover:bg-[#ff6636]">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M17.9507 5.29205C17.9086 4.33564 17.7539 3.67812 17.5324 3.10836C17.3038 2.50359 16.9522 1.96213 16.4915 1.51201C16.0414 1.05489 15.4963 0.699691 14.8986 0.474702C14.3255 0.253147 13.6714 0.0984842 12.715 0.0563159C11.7515 0.0105764 11.4456 0 9.00174 0C6.55791 0 6.25202 0.0105764 5.29204 0.0527447C4.33563 0.0949129 3.67811 0.249713 3.1085 0.471131C2.50358 0.699691 1.96213 1.05132 1.51201 1.51201C1.05489 1.96213 0.699827 2.50716 0.474701 3.10493C0.253147 3.67812 0.098484 4.33207 0.0563158 5.28848C0.0105764 6.25203 0 6.55792 0 9.00176C0 11.4456 0.0105764 11.7515 0.0527446 12.7115C0.0949128 13.6679 0.249713 14.3254 0.471267 14.8952C0.699827 15.4999 1.05489 16.0414 1.51201 16.4915C1.96213 16.9486 2.50715 17.3038 3.10493 17.5288C3.67811 17.7504 4.33206 17.905 5.28861 17.9472C6.24845 17.9895 6.55448 17.9999 8.99831 17.9999C11.4421 17.9999 11.748 17.9895 12.708 17.9472C13.6644 17.905 14.3219 17.7504 14.8916 17.5288C16.1012 17.0611 17.0577 16.1047 17.5254 14.8952C17.7468 14.322 17.9016 13.6679 17.9437 12.7115C17.9859 11.7515 17.9965 11.4456 17.9965 9.00176C17.9965 6.55792 17.9929 6.25203 17.9507 5.29205ZM16.3298 12.6411C16.2911 13.5202 16.1434 13.9949 16.0203 14.3114C15.7179 15.0956 15.0955 15.7179 14.3114 16.0204C13.9949 16.1434 13.5168 16.2911 12.6411 16.3297C11.6917 16.372 11.407 16.3824 9.00531 16.3824C6.60365 16.3824 6.31534 16.372 5.36937 16.3297C4.4903 16.2911 4.01559 16.1434 3.69913 16.0204C3.3089 15.8761 2.9537 15.6476 2.66539 15.3487C2.3665 15.0568 2.13794 14.7052 1.99372 14.315C1.87065 13.9985 1.72299 13.5202 1.68439 12.6447C1.64209 11.6953 1.63165 11.4104 1.63165 9.00876C1.63165 6.60709 1.64209 6.31878 1.68439 5.37295C1.72299 4.49387 1.87065 4.01917 1.99372 3.7027C2.13794 3.31234 2.3665 2.95727 2.66896 2.66883C2.9607 2.36994 3.31233 2.14138 3.7027 1.99729C4.01917 1.87422 4.49744 1.72656 5.37294 1.68783C6.32235 1.64566 6.60722 1.63508 9.00875 1.63508C11.414 1.63508 11.6987 1.64566 12.6447 1.68783C13.5238 1.72656 13.9985 1.87422 14.3149 1.99729C14.7052 2.14138 15.0604 2.36994 15.3487 2.66883C15.6476 2.96071 15.8761 3.31234 16.0203 3.7027C16.1434 4.01917 16.2911 4.49731 16.3298 5.37295C16.372 6.32236 16.3826 6.60709 16.3826 9.00876C16.3826 11.4104 16.372 11.6917 16.3298 12.6411Z" fill="white"/><path d="M9.00188 4.37744C6.44912 4.37744 4.37793 6.44849 4.37793 9.00139C4.37793 11.5543 6.44912 13.6253 9.00188 13.6253C11.5548 13.6253 13.6258 11.5543 13.6258 9.00139C13.6258 6.44849 11.5548 4.37744 9.00188 4.37744ZM9.00188 12.0008C7.34578 12.0008 6.00244 10.6576 6.00244 9.00139C6.00244 7.34515 7.34578 6.00195 9.00188 6.00195C10.6581 6.00195 12.0013 7.34515 12.0013 9.00139C12.0013 10.6576 10.6581 12.0008 9.00188 12.0008Z" fill="white"/><path d="M14.8876 4.19521C14.8876 4.79133 14.4043 5.27469 13.808 5.27469C13.2119 5.27469 12.7285 4.79133 12.7285 4.19521C12.7285 3.59894 13.2119 3.11572 13.808 3.11572C14.4043 3.11572 14.8876 3.59894 14.8876 4.19521Z" fill="white"/></svg>
                    </button>
                    <button class="p-[0.875rem] bg-[#363b4766] hover:shadow-[0px_6px_20px_0px_rgba(204,82,43,0.50)] hover:bg-[#ff6636]">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M17.992 18.0002V17.9994H17.9965V11.3979C17.9965 8.16841 17.3012 5.68066 13.5257 5.68066C11.7107 5.68066 10.4927 6.67666 9.99548 7.62091H9.94298V5.98216H6.36322V17.9994H10.0907V12.0489C10.0907 10.4822 10.3877 8.96716 12.328 8.96716C14.2397 8.96716 14.2682 10.7552 14.2682 12.1494V18.0002H17.992Z" fill="white"/><path d="M0.293488 5.98291H4.02549V18.0002H0.293488V5.98291Z" fill="white"/><path d="M2.15799 0C0.964741 0 -0.00350952 0.96825 -0.00350952 2.1615C-0.00350952 3.35475 0.964741 4.34325 2.15799 4.34325C3.35124 4.34325 4.31949 3.35475 4.31949 2.1615C4.31874 0.96825 3.35049 0 2.15799 0V0Z" fill="white"/></svg>
                    </button>
                    <button class="p-[0.875rem] bg-[#363b4766] hover:shadow-[0px_6px_20px_0px_rgba(204,82,43,0.50)] hover:bg-[#ff6636]">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#clip0_4523_17773)"><path d="M17.9965 3.73137C17.3271 4.025 16.6139 4.21962 15.8702 4.31412C16.6352 3.85737 17.2191 3.13962 17.4936 2.2745C16.7804 2.69975 15.9929 3.00013 15.1536 3.16775C14.4764 2.44663 13.5111 2 12.4581 2C10.4151 2 8.77036 3.65825 8.77036 5.69113C8.77036 5.98363 8.79512 6.26487 8.85587 6.53262C5.78799 6.383 3.07337 4.91263 1.24974 2.67275C0.931365 3.22513 0.744615 3.85738 0.744615 4.538C0.744615 5.816 1.40274 6.94887 2.38374 7.60475C1.79087 7.5935 1.20924 7.42138 0.71649 7.15025C0.71649 7.1615 0.71649 7.17613 0.71649 7.19075C0.71649 8.984 1.99562 10.4735 3.67299 10.8166C3.37262 10.8988 3.04524 10.9381 2.70549 10.9381C2.46924 10.9381 2.23074 10.9246 2.00687 10.8751C2.48499 12.3365 3.84174 13.4109 5.45499 13.4457C4.19949 14.4279 2.60537 15.0196 0.879615 15.0196C0.57699 15.0196 0.28674 15.0061 -0.00350952 14.969C1.63112 16.0231 3.56837 16.625 5.65749 16.625C12.448 16.625 16.1605 11 16.1605 6.12425C16.1605 5.96112 16.1549 5.80363 16.147 5.64725C16.8794 5.1275 17.4947 4.47837 17.9965 3.73137Z" fill="white"/></g><defs><clipPath id="clip0_4523_17773"><rect width="18" height="18" fill="white" transform="translate(-0.00350952)"/></clipPath></defs></svg>
                    </button>
                    <button class="p-[0.875rem] bg-[#363b4766] hover:shadow-[0px_6px_20px_0px_rgba(204,82,43,0.50)] hover:bg-[#ff6636]">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M16.0392 3.38548C16.8101 3.59312 17.4181 4.20094 17.6256 4.97204C18.0112 6.38048 17.9964 9.31629 17.9964 9.31629C17.9964 9.31629 17.9964 12.2371 17.6257 13.6457C17.4181 14.4167 16.8103 15.0246 16.0392 15.2321C14.6306 15.6029 8.99642 15.6029 8.99642 15.6029C8.99642 15.6029 3.37694 15.6029 1.95367 15.2174C1.18257 15.0098 0.57475 14.4018 0.36711 13.6309C-0.00354004 12.2371 -0.00354004 9.30146 -0.00354004 9.30146C-0.00354004 9.30146 -0.00354004 6.38048 0.36711 4.97204C0.574613 4.20108 1.1974 3.57829 1.95353 3.37079C3.36211 3 8.99629 3 8.99629 3C8.99629 3 14.6306 3 16.0392 3.38548ZM11.8878 9.30154L7.20251 12.0001V6.60303L11.8878 9.30154Z" fill="white"/></svg>
                    </button>
                </div>
            </div>
            <div class="sm:min-w-[12rem]">
                <h2 class="mb-[1.25rem] text-[#FFF] text-sm font-ralewayMedium leading-[100%] uppercase">top 4 category</h2>
                <div class="flex flex-col sm:items-start items-center">
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Development</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Finance & Accounting</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Design</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Business</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                </div>
            </div>
            <div class="sm:min-w-[12rem]">
                <h2 class="mb-[1.25rem] text-[#FFF] text-sm font-ralewayMedium leading-[100%] uppercase">Quick Links</h2>
                <div class="flex flex-col sm:items-start items-center">
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">About</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Become Instructor</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Contact</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Career</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                </div>
            </div>
            <div class="sm:min-w-[12rem]">
                <h2 class="mb-[1.25rem] text-[#FFF] text-sm font-ralewayMedium leading-[100%] uppercase">Support</h2>
                <div class="flex flex-col sm:items-start items-center">
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Help Center</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">FAQs</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Terms & Condition</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                    <button class="text-[#8C94A3] sm:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem] px-0 py-1.5 hover:shadow-[0px_-1.5px_0px_0px_#FF6636_inset] flex items-center sm:gap-3 gap-1.5 group">
                        <span class="group-hover:text-[#FFF]">Privacy Policy</span>
                        <svg class="hidden group-hover:flex" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2.5 8H13.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/><path d="M9 3.5L13.5 8L9 12.5" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>
                    </button>
                </div>
            </div>
            <div class="sm:min-w-[12rem]">
                <h2 class="mb-[1.25rem] text-[#FFF] text-sm font-ralewayMedium leading-[100%] uppercase">Downlaod our app</h2>
                <div class="flex flex-col items-start gap-2">
                    <button class="flex justify-center items-center sm:gap-3.5 gap-2 sm:px-5 px-2.5 sm:py-3 py-1.5 bg-[#363b4766]">
                        <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#clip0_4523_17823)"><path d="M21.9986 0C20.2926 0.117999 18.2986 1.20999 17.1366 2.63198C16.0766 3.92198 15.2046 5.83797 15.5446 7.69995C17.4086 7.75795 19.3346 6.63996 20.4506 5.19397C21.4946 3.84798 22.2846 1.94399 21.9986 0Z" fill="white"/><path d="M28.7406 10.7362C27.1026 8.68223 24.8006 7.49023 22.6266 7.49023C19.7566 7.49023 18.5427 8.86423 16.5487 8.86423C14.4927 8.86423 12.9307 7.49423 10.4487 7.49423C8.01071 7.49423 5.41473 8.98423 3.76874 11.5322C1.45475 15.1202 1.85075 21.8662 5.60073 27.6121C6.94272 29.6681 8.73471 31.9801 11.0787 32.0001C13.1647 32.0201 13.7527 30.6621 16.5787 30.6481C19.4046 30.6321 19.9406 32.0181 22.0226 31.9961C24.3686 31.9781 26.2586 29.4161 27.6006 27.3601C28.5626 25.8861 28.9206 25.1441 29.6666 23.4801C24.2406 21.4142 23.3706 13.6982 28.7406 10.7362Z" fill="white"/></g><defs><clipPath id="clip0_4523_17823"><rect width="32" height="32" fill="white"/></clipPath></defs></svg>
                        <div class="flex flex-col items-start gap-[0.125rem]">
                            <span class="text-[#B7BAC7] text-[0.625rem] leading-[0.625rem]">Download now</span>
                            <span class="text-white sm:text-base text-sm font-ralewayMedium leading-[1.375rem]">App Store</span>
                        </div>
                    </button>
                    <button class="flex justify-center items-center sm:gap-3.5 gap-2 sm:px-5 px-2.5 sm:py-3 py-1.5 bg-[#363b4766]">
                        <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M19.8024 9.76833L3.01889 0.123178C2.808 4.82537e-05 2.54267 0.00688879 2.33857 0.130018C2.12767 0.253148 1.99841 0.472045 1.99841 0.718304C1.99841 0.718304 2.00522 1.60757 2.01202 3.07145L14.2374 15.3639L19.8024 9.76833Z" fill="url(#paint0_linear_4523_17834)"/><path d="M2.01196 3.07129C2.03237 8.35219 2.0936 21.1714 2.12081 27.5536L14.2441 15.3637L2.01196 3.07129Z" fill="url(#paint1_linear_4523_17834)"/><path d="M29.4086 15.2889L19.8024 9.76855L14.2306 15.3641L20.5168 21.6848L29.4154 16.4723C29.6263 16.3492 29.7555 16.1234 29.7555 15.884C29.7555 15.6377 29.6195 15.412 29.4086 15.2889Z" fill="url(#paint2_linear_4523_17834)"/><path d="M2.11414 27.5536C2.12774 29.8315 2.13455 31.2885 2.13455 31.2885C2.13455 31.5348 2.26381 31.7605 2.47471 31.8768C2.6856 31.9999 2.94413 31.9999 3.15503 31.8768L20.5236 21.6913L14.2374 15.3706L2.11414 27.5536Z" fill="url(#paint3_linear_4523_17834)"/><defs><linearGradient id="paint0_linear_4523_17834" x1="1.99841" y1="7.70208" x2="19.8055" y2="7.70208" gradientUnits="userSpaceOnUse"><stop stop-color="#63BE6B"/><stop offset="0.506" stop-color="#5BBC6A"/><stop offset="1" stop-color="#4AB96A"/></linearGradient><linearGradient id="paint1_linear_4523_17834" x1="2.0087" y1="15.3154" x2="14.237" y2="15.3154" gradientUnits="userSpaceOnUse"><stop stop-color="#3EC6F2"/><stop offset="1" stop-color="#45AFE3"/></linearGradient><linearGradient id="paint2_linear_4523_17834" x1="14.2371" y1="15.731" x2="29.7539" y2="15.731" gradientUnits="userSpaceOnUse"><stop stop-color="#FAA51A"/><stop offset="0.387" stop-color="#FAB716"/><stop offset="0.741" stop-color="#FAC412"/><stop offset="1" stop-color="#FAC80F"/></linearGradient><linearGradient id="paint3_linear_4523_17834" x1="2.11713" y1="23.6696" x2="20.5233" y2="23.6696" gradientUnits="userSpaceOnUse"><stop stop-color="#EC3B50"/><stop offset="1" stop-color="#E7515B"/></linearGradient></defs></svg>
                        <div class="flex flex-col items-start gap-[0.125rem]">
                            <span class="text-[#B7BAC7] text-[0.625rem] leading-[0.625rem]">Download now</span>
                            <span class="text-white sm:text-base text-sm font-ralewayMedium leading-[1.375rem]">Play Store</span>
                        </div>
                    </button>
                </div>
            </div>
        </div>
        <div class="md:py-6 py-3 shadow-[0px_1px_0px_0px_rgba(54,59,71,0.50)_inset] w-full">
            <div class="flex sm:justify-between md:flex-row flex-col justify-center md:gap-16 gap-1.5 sm:text-start text-center items-center flex-wrap container mx-auto md:px-0 px-5">
                <span class="text-[#8C94A3] md:text-sm text-xs leading-[1.375rem] tracking-[-0.00875rem]">© 2023 - Eduflex. Coded by <button class="text-white">Lazri Ossama</button>. All rights reserved</span>
                <select name="" id="" class="pl-[1.125rem] w-full md:max-w-[12.5rem] max-w-[6.25rem] cursor-pointer sm:pr-4 pr-2 sm:py-3 py-1.5 bg-inherit border border-[#363B47] border-solid bg-[#1d2026] outline-none text-[#8C94A3] leading-6 sm:text-base text-sm">
                    <option value="English">English</option>
                    <option value="French">French</option>
                </select>
            </div>
        </div>
    </footer>
  
</div>