<script setup>
import { Head, Link } from '@inertiajs/vue3';


</script>

<template>
    <Head title="Upload" />
    <nav class="relative sticky top-0 bg-white shadow-md px-4 py-4 flex justify-between items-center bg-white">
		<a class="text-2xl font-bold leading-none" href="/">
			REGEX-APP
		</a>
    <div  >
    <Link 
        type="button" class=" hidden lg:inline-block lg:ml-auto lg:mr-3 py-2 px-6 text-sm text-dark ">
          mole@gmail.com
    </Link>
    
    <Link 
          class="favorite hidden lg:inline-block lg:ml-auto lg:mr-3 py-2 px-6 bg-gray-20 hover:bg-gray-200 text-sm text-gray-900 font-bold transition duration-200">
            <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg> Favourites
    </Link>

    <Link href="/upload"
                class="upload hidden lg:inline-block lg:ml-auto lg:mr-3 py-2 px-6 bg-gray-200 hover:bg-gray-300 text-sm text-dark font-bold transition duration-200"
        >Upload
    </Link>
    <Link 
            class="logout hidden lg:inline-block py-2 px-6 bg-gray-600 hover:bg-gray-700 text-sm text-white font-bold transition duration-200"
            >Logout
    </Link>



 
    </div>	
</nav>
	<section class="py-6 dark:bg-gray-800 dark:text-gray-50">
        <div class="head-title"><h2>UPLOAD YOUR IMAGE</h2></div>
		<div class="upload-card flex justify-center ">
		
			<form novalidate="" class="flex flex-col py-6 space-y-6 md:py-0 md:px-6 ng-untouched ng-pristine ng-valid">
				<label class="block">
					<span class="label mb-1"><center>UPLOAD IMAGE</center></span>
					<input type="file"  class="block w-full rounded-md shadow-sm focus:ring focus:ring-opacity-75 focus:ring-violet-50 dark:bg-gray-800">
				</label>
				<label class="block">
					<span class="label mb-1"><center>TITLE</center></span>
					<input type="text" placeholder="IMAGE TITLE" class="block w-full shadow-sm focus:ring focus:ring-opacity-75 focus:ring-violet-50 dark:bg-gray-800">
				</label>
				<label class="block">
					<span class="label mb-1"><center>DESCRIPTION</center></span>
					<input type="text" placeholder="IMAGE DESCRIPTION" class="block w-full shadow-sm focus:ring focus:ring-opacity-75 focus:ring-violet-50 dark:bg-gray-800">	
				</label>
				<button type="button" class="submit-post px-8 py-3 text-lg bg-gray-600 hover:bg-gray-700 text-sm text-white font-bold transition duration-200">UPLOAD</button>
			</form>
		</div>
	</section>



</template>
<style>

.head-title{
    text-align: center;
    padding: 20px 20px 20px 0px;
    font-weight: bolder;
    font-size: 25px;
}
.upload-card{
    

}
.label{
    text-align: center;
    font-weight: bolder;
}
.favorite{
    border: 1px solid black;
    border-radius: 5px;
}
.upload{
    border-radius: 5px;
    width: 150px;
    text-align: center;
}
.login{
    border-radius: 5px;
    width: 150px;
    text-align: center;
}
.logout{
    border-radius: 5px;
    width: 150px;
    text-align: center;

}
.register{
    border-radius: 5px;
    width: 150px;
    text-align: center;

}
.submit-post{
    border-radius: 30px;
    width: 100%;
    text-align: center;
    display: inline-block;

}
input::-webkit-input-placeholder {
  font-size: 10px;
  position: relative;
  top: -4px;
  text-align: center;
}
span{
    position: relative;
    text-align: center;
}

input::-webkit-file-upload-button {
  padding: 10px;
  width: 100%;
  position: relative;
  text-transform: uppercase;
}

</style>