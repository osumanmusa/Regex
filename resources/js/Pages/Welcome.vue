<script setup>
import { Head, Link } from '@inertiajs/vue3';


</script>

<template>
    <Head title="Welcome" />
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
            Moderation
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
<div class="title-header"><h3><b>IMAGE MODERATION</b></h3></div>
    
 <!-- container starts here -->
    <div class="container">
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->
        <!-- box item starts here-->
        <div class="box">
            <img src="img/1.png" alt="image" />
            <h2 class="title"><b>Title: first Immage</b></h2>
            <p>Description : Lorem, ipsum dolor sit amet co consequatur! Perspiciatis vel labore qui in repudiandae repellendus non ad inventore asperiores sequi placeat sapiente excepturi, facilis, exercitationem tempora, rerum dicta.</p>
            <button class="add-button">
                <svg width="30px" height="18px" viewBox="0 0 24 24" fill="none" class="inline-block" xmlns="http://www.w3.org/2000/svg">
                <path d="M12.7692 6.70483C9.53846 2.01902 4 3.90245 4 8.68256C4 13.4627 13.2308 20 13.2308 20C13.2308 20 22 13.2003 22 8.68256C22 4.16479 16.9231 2.01903 13.6923 6.70483L13.2308 7.0791L12.7692 6.70483Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>Add favourite</button>

        </div>
        <!-- box item ends here-->

    </div>

 <!-- container ends here -->
 

</template>
<style>
.container{
    width: 1200px;
    margin: 0px auto;
    columns: 4;
    column-gap: 10px;
}
.box{
    width: 250px;
    padding: 20px 10px 20px 10px;
    background-color: rgb(255, 255, 255);
    border: 1px solid grey;
    margin-bottom: 10px;
    break-inside: avoid;

}
.box img{
    width: 100%;
    height: 170px;
    object-fit: contain;

}
.add-button{
    background-color: rgb(255, 255, 255);
    color: black;
    border: 1px solid grey;
    padding: 10px;
    display: inline-block;
    letter-spacing: 2px;
    text-decoration: none;
    overflow: hidden;
    border-radius: 5px;
    width: 100%;
}
.add-button:hover{
    
    color: #111;
    background: rgb(246, 245, 245);
    box-shadow: 0 0 1px #6a6a69;
}
.box p{
    padding: 0px 20px 20px 0px;
    text-align: justify;
    text-justify: distribute;
    text-align-last: left;
    hyphens: auto;
    word-spacing: -0.05em;
}
.title{
    padding: 20px 20px 20px 0px;
}
.title-header{
    text-align: center;
    padding: 20px 20px 20px 0px;
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

</style>
