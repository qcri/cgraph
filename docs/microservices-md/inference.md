[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/dae921c2076893b36d88)
<div id="swagger-ui"></div>
<style> .swagger-ui .scheme-container, .swagger-ui .topbar { display: none !important; } </style>
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/swagger-ui/3.27.0/swagger-ui.css">
<script src="../../assets/swagger-ui-bundle.js"></script>
<!-- <script src="../../assets/swagger-ui.min.js"></script> -->
<script src="../../assets/swagger-ui-standalone-preset.js"></script>
<script>
window.onload = function() {
  // Begin Swagger UI call region
  const ui = SwaggerUIBundle({
    url: "../../microservices-yaml/inference.yml ",
    dom_id: '#swagger-ui',
    deepLinking: true,
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIStandalonePreset
    ],
    layout: "StandaloneLayout"
  })
  window.ui = ui
}
</script>