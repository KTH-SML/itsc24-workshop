<script>
    import Section from "./Section.svelte";
</script>

<div class="rounded-lg bg-white px-5 py-6 shadow-md sm:px-6">
    <div class="pb-10 px-2 flex">
        <p class="grow text-center"><b>Date: </b>September 24, 2024 </p>
        <p class="grow text-center"><b>Room: </b>Salon 19</p>
    </div>
    
    <Section title="Abstract">
        <div class="overflow-hidden">
            <div class="w-1/3 aspect-square pl-6 pb-6 float-right">
                <img class="object-cover rounded shadow" src="svea.jpeg" alt="Small-Scale vehicle under testing">
            </div>
            <p class="text-justify">The growing importance of Connected and Automated Vehicles (CAVs) calls for innovative platforms to develop, test, and validate new algorithms and technologies. Small-scale testbeds offer an effective means to prototype and experiment with close to real-world conditions. Furthermore, these platforms tend to be powerful research demonstrators that motivate collaborations within and outside academia. However, these testbeds present unique challenges in terms of accessibility, reproducibility, and integration into educational frameworks. To better approach these challenges, this workshop aims to facilitate discussions on learnings and best practices. In particular, the workshop focuses on addressing these issues with an emphasis on leveraging small-scale testbeds for research and education.</p>
        </div>
    </Section>
    
    <Section title="Program">
        <div class="overflow-x-auto">
            <table class="table">
                <!-- head -->
                <thead>
                <tr><th>Time</th> <th>Event</th></tr>
                </thead>
                <tbody>
                <!-- row 0 -->
                <tr>
                    <td>08:50 - 09:00</td>
                    <td>Opening Remarks</td>
                </tr>
                <!-- Speaker 1 -->
                <tr>
                    <td class="whitespace-nowrap">10:15 - 10:45</td>
                    <td><b>Andreas Malikopoulos</b> (Cornell University)<br>
                        A Research and Educational Scaled, Smart City Testbed for Real-Time Control of Autonomous Driving Systems</td>
                </tr>
                <!-- Speaker 2 -->
                <tr>
                    <td class="whitespace-nowrap">09:00 - 09:30</td>
                    <td><b>Jianye Xu</b> (RWTH Aachen University)<br>
                        Cyber-Physical Mobility Lab: An Open-Source Testbed for Connected and Automated Vehicles</td>
                </tr>
                <!-- Break -->
                <tr>
                    <td class="whitespace-nowrap">10:00 - 10:15</td>
                    <td>Coffee Break</td>
                </tr>
                <!-- Speaker 3 -->
                <tr>
                    <td class="whitespace-nowrap">09:30 - 10:00</td>
                    <td><b>Simon Thompson</b> (TIER IV)<br>
                        Autoware Reference Platforms: From Small Scale to Full Scale Autonomous Vehicles</td>
                </tr>
                <!-- Speaker 4 -->
                <tr>
                    <td class="whitespace-nowrap">10:45 - 11:15</td>
                    <td><b>Kaj Munhoz Arfvidsson</b> (KTH Royal Institute of Technology)<br>
                        SVEA and Recent Experiences With Small-Scale Vehicles in Industrial Collaborations</td>
                </tr>
                <!-- Discussion -->
                <tr>
                    <td class="whitespace-nowrap">11:15 - 12:00</td>
                    <td><b>Panel Discussion</b><br>
                        Moderated by Jonas Mårtensson</td>
                </tr>
                </tbody>
            </table>
        </div>
    </Section>
    
    <Section title="Contact">
        <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-8 px-4">
            <div class="flex items-center px-4">
                <div class="avatar">
                    <div class="w-16 rounded">
                        <img src="https://www.kth.se/files/avatar/kajarf" />
                    </div>
                </div>
                <div class="ml-3">
                    <p class="text-l font-medium text-gray-700 group-hover:text-gray-900">Kaj Munhoz Arfvidsson</p>
                    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">KTH Royal Institute of Technology</p>
                    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">kajarf@kth.se</p>
                </div>
            </div>
            <div class="flex items-center px-4">
                <div class="avatar">
                    <div class="w-16 rounded">
                        <img src="https://www.kth.se/files/avatar/jonas1" />
                    </div>
                </div>
                <div class="ml-3">
                    <p class="text-l font-medium text-gray-700 group-hover:text-gray-900">Jonas Mårtensson</p>
                    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">KTH Royal Institute of Technology</p>
                    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">jonas1@kth.se</p>
                </div>
            </div>
        </div>
    </Section>
</div>
