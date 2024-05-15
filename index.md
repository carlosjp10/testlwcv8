<html>
    <style>
        a {
            color:orange;
        }
    </style>

    <script src="https://resourceful-narwhal-fhwyw8-dev-ed.trailblaze.my.site.com/formulario/lightning/lightning.out.js"></script>
    </script>
    <div data-lightning-out="true"></div>

    <script>
        const appName = 'c:CorretoraFormWrapper';
        const componentName = 'c:CorretoraForm';
        const lightningEndpoint = 'https://resourceful-narwhal-fhwyw8-dev-ed.trailblaze.my.site.com';
        const targetElement = document.querySelector("[data-lightning-out]");
        const componentAttributes = {

        };

        $Lightning.use(
            appName,
            function(){
                $Lightning.createComponent(
                    componentName,
                    componentAttributes,
                    targetElement,
                    function(cmp){
                        console.log('@cac funcionando');
                    }
                );
            },
            lightningEndpoint
        );
    </script>
</html>
