<script setup>
defineProps({
    client: Object
})
</script>

<template>
     <div class="">
            <div class="">
                <div class="">
                    <div class="p-6 text-gray-900">

                        <div class="bg-gray-800 text-black m-5 p-5 rounded-lg" style="width: 300px;">
                                <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" alt="">
    <div class="min-w-[200px] mb-4 mx-2 p-4 bg-white rounded shadow border flex-1 cursor-pointer">

            <b>Last Name: </b>{{ client.last_name }} <br>
            <b>First Name: </b>{{ client.first_name }} <br>
             <b>Client Address: </b>{{ client.address }} <br>
            <b>Phone Number: </b>{{ client.phone }} <br>

    </div>
    </div>
    </div>
    </div>
    </div>
    </div>
</template>
