<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link rel="stylesheet" href="./custom.css">
<style>
    .slds-visual-picker_vertical .slds-visual-picker__figure {
        height: inherit !important;
    }

    .runtime_appointmentbookingFlowLocation .slds-visual-picker_vertical {
        display: inline-flex !important;
    }
</style>
</head>
<body>
<div id="lexcontainer">
</div>
<script src="https://haporg--apmdev.sandbox.my.site.com/lightning/lightning.out.js"></script>  
<script>
    var Str1 = window.location.href;    // added this line for read web URL, because based on web URL in salesforce for assign work type to appointment
   document.write(Str1 + "</br>" );
    var inputVariables = [
         { name : "inputVariables", type : "String", value: Str1 } // by using this line we are assigning the web URL to variable.

       ];
$Lightning.use("runtime_appointmentbooking:lightningOutGuest",
    function() {                  // Callback once framework and app load
        $Lightning.createComponent(
            "lightning:flow",    // top-level component of your app
            { },    // attributes to set on the component when created
            "lexcontainer",    // the DOM location to insert the component
            function(component) {            // API name of the Flow
                component.startFlow("Inbound_New_Guest_Appointment_Custom",inputVariables); // calling the scheduler flow and passing URL value with inputVariables.
            }
        );
    },    'https://haporg--apmdev.sandbox.my.site.com/'  // this URL will change, for testing purpose we given dev URL.
);
</script>

</body>
</html>
