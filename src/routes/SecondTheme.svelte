<script>
    import Section from "./Section.svelte";
</script>

<div class="rounded-lg bg-white px-5 py-6 shadow-md sm:px-6">
    <div class="pb-10 px-2 flex">
        <p class="grow text-center"><b>Date: </b>September 24, 2024 </p>
        <p class="grow text-center"><b>Room: </b>Salon 20</p>
    </div>
    
    <Section title="Abstract">
        <div class="overflow-hidden">
            <p class="text-justify">The workshop focuses on the transformative potential of artificial intelligence and advanced decision-making technologies in modern transportation. As urban environments evolve and demand smarter mobility solutions, this workshop will explore how AI, data analytics, and intelligent systems can enhance traffic management, road safety, and autonomous driving.</p>
            <p class="text-justify">Through a series of expert-led discussions, the workshop will cover topics such as leveraging real-world vehicle data, the development of digital twins for transportation modeling, the integration of reinforcement learning with planning and control systems, and ensuring robustness and trust in AI explanations for autonomous vehicles. Participants will gain insights into the latest advancements in smart mobility, offering a forward-looking view on the future of transportation systems.</p>
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
                    <td>13:20 - 13:30</td>
                    <td>Opening Remarks</td>
                </tr>
                <!-- Speaker 1 -->
                <tr>
                    <td class="whitespace-nowrap">13:30 - 14:00</td>
                    <td><b>Lavanya Sayam</b> (IEEE National Transportation Data & Analytics Solutions)<br>
                        IEEE NTDAS: Driving global roadways research with real-world vehicle data analytics platform</td>
                </tr>
                <!-- Speaker 2 -->
                <tr>
                    <td class="whitespace-nowrap">14:00 - 14:30</td>
                    <td><b>Yunchen Ge and Marcelo Contreras Cabrera</b> (University of Alberta)<br>
                        Development a Digital Twin Visualizer for Intelligent Transportation Applications</td>
                </tr>
                <!-- Break -->
                <tr>
                    <td class="whitespace-nowrap">14:30 - 15:00</td>
                    <td>Coffee Break</td>
                </tr>
                <!-- Speaker 3 -->
                <tr>
                    <td class="whitespace-nowrap">15:00 - 15:30</td>
                    <td><b>Matthew E. Taylor</b> (University of Alberta)<br>
                        Integrating Reinforcement learning, with planning, control, and human input</td>
                </tr>
                <!-- Speaker 4 -->
                <tr>
                    <td class="whitespace-nowrap">15:30 - 16:00</td>
                    <td><b>Randy Goebel and Shahin Atakishiyev</b> (University of Alberta)<br>                        
                        Robustness Analysis of Interactive Explanations for Traffic Scene Understanding: Implications for Trust in Autonomous Driving</td>
                </tr>
                <!-- Discussion -->
                <tr>
                    <td class="whitespace-nowrap">16:00 - 16:45</td>
                    <td><b>Panel Discussion</b><br>
                        Moderated by Ehsan Hashemi</td>
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
                        <img src="https://apps.ualberta.ca/directory/person/profile_photo/ehashemi" />
                    </div>
                </div>
                <div class="ml-3">
                    <p class="text-l font-medium text-gray-700 group-hover:text-gray-900">Ehsan Hashemi</p>
                    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">University of Alberta</p>
                    <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">ehashemi@ualberta.ca</p>
                </div>
            </div>
        </div>
    </Section>
</div>
