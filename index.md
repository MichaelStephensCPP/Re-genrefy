<nav class="navbar navbar-inverse navbar-fixed-top">
   <div class="container">
      <div class="navbar-header">
         <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
         <span class="sr-only">Toggle navigation</span>
         <span class="icon-bar"></span>
         <span class="icon-bar"></span>
         <span class="icon-bar"></span>
         </button>
         <a class="navbar-brand" href="#">Project name</a>
        
## Homepage

$( document ).ready(function() {
  $('[data-toggle=search-form]').click(function() {
      $('.search-form-wrapper').toggleClass('open');
      $('.search-form-wrapper .search').focus();
      $('html').toggleClass('search-form-open');
    });
    $('[data-toggle=search-form-close]').click(function() {
      $('.search-form-wrapper').removeClass('open');
      $('html').removeClass('search-form-open');
    });
  $('.search-form-wrapper .search').keypress(function( event ) {
