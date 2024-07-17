<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="./custom.css">
</head>
<body>
<main>
<div id=''>
<p>flow here</p>
</div>
<script type='text/javascript' src="
https://haporg--apmdev.sandbox.lightning.force.com/lightning/lightning.out.js"></script>
<script>
        $Lightning.use("runtime_appointmentbooking:lightningOutGuest",
            function() {                  // Callback once framework and app load
                $Lightning.createComponent(
                    "lightning:flow",    // top-level component of your app
                    { },    // attributes to set on the component when created
                    "lexcontainer",    // the DOM location to insert the component
                    function(component) {            // API name of the Flow
                        component.startFlow("Inbound_New_Guest_Appointment_Custom");
                    }
                );
            },
'https://haporg--apmdev.sandbox.lightning.force.com/'
  // Site endpoint
        );
</script>
</main>
</body>
</html>
