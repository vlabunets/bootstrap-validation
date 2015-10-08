# bootstrap-validation
bootstrap validation addon

how to use here:
http://formvalidation.io/getting-started

<!-- Bootstrap CSS v3.0.0 or higher -->
<link rel="stylesheet" href="/vendor/bootstrap/css/bootstrap.min.css">

<!-- FormValidation CSS file -->
<link rel="stylesheet" href="/vendor/formvalidation/dist/css/formValidation.min.css">

<!-- jQuery v1.9.1 or higher -->
<script type="text/javascript" src="/vendor/jquery/jquery.min.js"></script>

<!-- Bootstrap JS -->
<script src="/vendor/bootstrap/js/bootstrap.min.js"></script>

<!-- FormValidation plugin and the class supports validating Bootstrap form -->
<script src="/vendor/formvalidation/dist/js/formValidation.min.js"></script>
<script src="/vendor/formvalidation/dist/js/framework/bootstrap.min.js"></script>
Don't confuse bootstrap(.min).js file provided by the Bootstrap framework with bootstrap(.min).js provided by FormValidation which is placed inside the formvalidation/dist/js/framework directory.

They are two different files and both of them need to be included as mentioned above.
