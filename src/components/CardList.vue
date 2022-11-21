
<template>
    <div class="flex flex-row mt-10">
        <div class="flex flex-1 flex-col justify-center mt-9 ml-12">
            <div class="flex justify-center">
            <img src="@/assets/images/LIST UNGU.png" alt="image" width="60px" height="30px"/>
            </div>
            <div class="flex flex-col mt-2 mr-12 ml-12">
            <h1 class="text-center text-xl font-bold text-black">Use Cases</h1>
            </div>
        </div>
        <div class="flex justify-end">
            <img src="@/assets/images/Ornamen Bulat Tengah.png" alt="image" width="60px" height="50px">
        </div>
    </div>
    <div class="flex-1 grid grid-cols-3 ml-10 mr-10 mt-10">
        <ul id="cardlist">
            <div class="card w-96 bg-base-100 shadow-xl">
                <figure>
                    <img src="@/assets/images/Foto/Foto 1.png" alt="Shoes" class="rounded-xl" />
                </figure>
                <div class="card-body items-start text-start">
                    <h2 class="card-title">Shoes!</h2>
                    <p>If a dog chews shoes whose shoes does he choose?</p>
                    <div class="card-actions justify-start mt-4">
                        <h2 class="text-l font-semibold text-rose-900">View Journey</h2>
                        <img src="@/assets/images/right-arrow.png " alt="image" width="20px" height="20px" class="mt-1">
                    </div>
                </div>
            </div>
        </ul>
    </div>
</template>