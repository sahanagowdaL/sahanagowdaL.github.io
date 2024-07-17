<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link rel="stylesheet" href="./custom.css">
    </head>
    <body>
        <h1>My External Page</h1>
        <div id="lightning-out"> <h1> Test Text </h1> </div>
        <script src="https://sahanagowdal.github.io//scheduleappointment/lightning/lightning.out.js"></script>
        <script>
            $Lightning.use("runtime_appointmentbooking:lightningOutGuest",
                //'c:MyLightningOutApp', // name of the Lightning Out app
                function () { // callback after the framework and app load
                    $Lightning.createComponent(
                       "lightning:flow", // top-level component of the Lightning Out app
                        {}, // attributes to set on the component
                        'lightning-out', // DOM element ID where the component is inserted
                        function (cmp) { // callback after the component loads
                            component.startFlow("Guest_New_Appointment");
                            //console.log('The component was created.');
                        }
                    );
                },
                'https://haporg--devmerge.sandbox.my.site.com/scheduleappointment' // Experience Cloud site endpoint
            );
        </script>
    </body>
</html>
