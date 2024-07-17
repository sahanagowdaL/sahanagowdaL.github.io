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
<p>Invoke the Lightning Component specified in the Script.</p>
</div>
<h1>My External Page</h1>
<script src="https://haporg--devmerge.sandbox.my.site.com/scheduleappointment/lightning/lightning.out.js"></script>
<h1>My External Page</h1>
<script>
    $Lightning.use("runtime_appointmentbooking:lightningOutGuest",
        function() {                  // Callback once framework and app load
            $Lightning.createComponent(
                "lightning:flow",    // top-level component of your app
                { },    // attributes to set on the component when created
                "lexcontainer",    // the DOM location to insert the component
                function(component) {            // API name of the Flow
                    component.startFlow("Salesforce_Scheduler_Unauthenticated");
                }
            );
        },    'https://haporg--devmerge.sandbox.my.site.com/'  // Site endpoint
    );
</script>

    </body>
</html>
