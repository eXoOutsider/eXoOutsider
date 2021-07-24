<html lang="en">
 <head> 
  <title>Instacart</title> 
  <meta content="Shop and deliver groceries and everyday essentials with Instacart. Set your own schedule, be a household hero, and earn money quickly. Get started with your application to be an Instacart shopper today." name="description"> 
  <meta content="width=device-width, initial-scale=1.0, user-scalable=no" name="viewport"> 
  <meta name="csrf-param" content="authenticity_token"> 
  <meta name="csrf-token" content="G1eLKQDEQSKoZEOJU/F2NOeiOHyPUYoD0GT9Ui1fjAqBoiI+IpwJn5vFbr+1W9nSzvhkKoMZ6qxuN6GhYpmcEA=="> 
  <link rel="stylesheet" media="screen" href="//netdna.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css"> 
  <link rel="stylesheet" media="all" href="https://d2nkqaulr5muje.cloudfront.net/assets/applicants/secure_forms-b0dcd3cfb1bf5e777c865cfdaaf3252f3c86614232368b2730d8b0df3351663f.css"> 
  <link rel="stylesheet" media="screen" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-datepicker/1.6.1/css/bootstrap-datepicker.standalone.min.css"> 
  <script>
    window.sentryDsn = "https://a86c0224c79849eda17e2ebb2e5c9dda@o502263.ingest.sentry.io/5613870";
    window.sentryEnvironment = "production";
    window.sentryRelease = "shoppers@0882dad91198a067152a20fb994bf3c7990bb1e3";
    window.sentryService = "applicants.web.shoppers.shoppers";
    window.sentryHost = "0xfulfillment.14583.applicants.web.shoppers.shoppers.fulfillment.pika.ac";
    window.sentryBranch = "master";
    window.sentryOwner = "shopper_success"

    window.sentryUser = {};

    (function(c,u,v,n,p,e,z,A,w){function k(a){if(!x){x=!0;var l=u.getElementsByTagName(v)[0],d=u.createElement(v);d.src=A;d.crossorigin="anonymous";d.addEventListener("load",function(){try{c[n]=r;c[p]=t;var b=c[e],d=b.init;b.init=function(a){for(var b in a)Object.prototype.hasOwnProperty.call(a,b)&&(w[b]=a[b]);d(w)};B(a,b)}catch(g){console.error(g)}});l.parentNode.insertBefore(d,l)}}function B(a,l){try{for(var d=m.data,b=0;b<a.length;b++)if("function"===typeof a[b])a[b]();var e=!1,g=c.__SENTRY__;"undefined"!==
    typeof g&&g.hub&&g.hub.getClient()&&(e=!0);g=!1;for(b=0;b<d.length;b++)if(d[b].f){g=!0;var f=d[b];!1===e&&"init"!==f.f&&l.init();e=!0;l[f.f].apply(l,f.a)}!1===e&&!1===g&&l.init();var h=c[n],k=c[p];for(b=0;b<d.length;b++)d[b].e&&h?h.apply(c,d[b].e):d[b].p&&k&&k.apply(c,[d[b].p])}catch(C){console.error(C)}}for(var f=!0,y=!1,q=0;q<document.scripts.length;q++)if(-1<document.scripts[q].src.indexOf(z)){f="no"!==document.scripts[q].getAttribute("data-lazy");break}var x=!1,h=[],m=function(a){(a.e||a.p||a.f&&
      -1<a.f.indexOf("capture")||a.f&&-1<a.f.indexOf("showReportDialog"))&&f&&k(h);m.data.push(a)};m.data=[];c[e]=c[e]||{};c[e].onLoad=function(a){h.push(a);f&&!y||k(h)};c[e].forceLoad=function(){y=!0;f&&setTimeout(function(){k(h)})};"init addBreadcrumb captureMessage captureException captureEvent configureScope withScope showReportDialog".split(" ").forEach(function(a){c[e][a]=function(){m({f:a,a:arguments})}});var r=c[n];c[n]=function(a,e,d,b,f){m({e:[].slice.call(arguments)});r&&r.apply(c,arguments)};
      var t=c[p];c[p]=function(a){m({p:a.reason});t&&t.apply(c,arguments)};f||setTimeout(function(){k(h)})})(window,document,"script","onerror","onunhandledrejection","Sentry","a86c0224c79849eda17e2ebb2e5c9dda","https://d2nkqaulr5muje.cloudfront.net/assets/vendor/sentry-6.7.2-bundle.min.js",{"dsn":"https://a86c0224c79849eda17e2ebb2e5c9dda@o502263.ingest.sentry.io/5613870"});

      Sentry.onLoad(function() {
        Sentry.init({
          dsn: window.sentryDsn,
          environment: window.sentryEnvironment,
          release: window.sentryRelease,
          attachStacktrace: true,
          beforeSend: function(event) {
            var unhandledRejectionException = event.exception &&
              event.exception.values &&
              event.exception.values.length &&
              event.exception.values[0].type === 'UnhandledRejection' &&
              event.exception.values[0].value.includes('Non-Error promise rejection captured with value:');

            var isAppsPage = event.request &&
              event.request.url &&
              event.request.url.includes('/apps');

            if (isAppsPage && unhandledRejectionException) {
              return null;
            }

            return event;
          },
          ignoreErrors: ["Script error", "Network Error", "Invalid argument", "Access is denied",
            "Error calling method on NPObject", "NS_ERROR_UNEXPECTED", "Can't find variable: __gCrWeb",
            "evaluating 'this.Ib.remove'", "find variable: $", "Blocked a frame with origin", "Cannot read property 'indexOf' of null"],
        });

        Sentry.configureScope(function(scope) {
          scope.setTag("instacart-owner", window.sentryOwner);
          scope.setTag("service", window.sentryService);
          scope.setTag("host", window.sentryHost);
          scope.setTag("branch", window.sentryBranch);
        });

        Sentry.setUser(window.sentryUser);
      });
      Sentry.forceLoad();
  </script> 
  <script>
//<![CDATA[
window.gon={};gon.widgetTextMain="Drag files here or click to add a file";gon.widgetTextFilesNotDone="Please wait until all files are done uploading";gon.widgetTextServerWorking="Still working... wait a few seconds and try again";gon.widgetTextCompleted="Completed";gon.sendSafelyHost="https://secure.instacart.com";gon.sendSafelyDropzoneId="o5-BtNuZuRehHRGEWrXRG2LuWd6iK9unh1JXDqn9qhs";
//]]>
</script> 
 </head> 
 <body class="secure_forms show_form android chrome mobile" id="secure_forms"> 
  <header class="center-logo"></header> 
  <div class="container"> 
   <p>The safety and security of all user accounts is very important to us. The following form is for Instacart shoppers who have had their information changed and are unable to login to their account. If you suspect someone else may have accessed your account and you’re no longer able to log in, please fill out the following form and our Trust &amp; Safety team can help you regain access. All information in this form is fully encrypted.</p> 
   <p>If you have forgotten your password, your account has been deactivated, or you have other account issues, please do not use this form. You will not receive a reply if you fill out this form for an unrelated reason.</p> 
   <form id="dropzone_form" name="dropzone_form"> 
    <div class="form-group"> 
     <label for="secure_full_name">Your full name</label> 
     <input class="form-control" id="secure_full_name" name="secure_full_name" type="text"> 
    </div> 
    <div class="form-group"> 
     <label for="secure_mail">Email address on your shopper profile</label> 
     <input class="form-control" id="secure_mail" name="secure_mail" type="text"> 
    </div> 
    <div class="form-group"> 
     <label for="secure_phone_number">Phone number on your shopper profile</label> 
     <input class="form-control" id="secure_phone_number" name="secure_phone_number" type="text"> 
    </div> 
    <div class="form-group"> 
     <label for="secure_issue">What is the account security issue you are having with your account?</label> 
     <select class="form-control" id="issue_selector"> <option>Suspected account takeover:</option> <option>Report a phishing scheme:</option> </select> 
     <input id="secure_issue" name="secure_issue" style="display:none" type="text" value="Suspected account takeover:"> 
     <ul> 
      <li> <strong>Suspected account takeover:</strong> unauthorized credential changes on your account or unauthorized use of your account. </li> 
      <li> <strong>Report a phishing scheme:</strong> someone contacted you via phone or email in an effort to gain access to your shopper account. </li> 
     </ul> 
    </div> 
    <div class="form-group"> 
     <label for="secure_subject">Subject</label> 
     <input class="form-control" id="secure_subject" name="secure_subject" type="text"> 
    </div> 
    <div class="form-group"> 
     <label for="secure_description">Description</label> 
     <textarea class="form-control" id="secure_description" name="secure_description" rows="3" type="text"></textarea> 
    </div> 
    <div class="form-group"> 
     <label for="secure_most_recent_account_access">Most recent date you were able to access your account</label> 
     <input class="form-control" id="secure_most_recent_account_access" name="secure_most_recent_account_access" type="text"> 
    </div> 
    <div class="form-group"> 
     <label for="secure_ssn"> To verify your identity, what are the last 4 numbers of your Tax Identification Number (TIN) or Social Security Number (SSN) <span class="badge badge-pill badge-info ml-1">ENCRYPTED</span> </label> 
     <input class="form-control" id="secure_ssn" maxlength="4" name="secure_ssn" type="password"> 
    </div> 
    <div class="form-group"> 
     <label for="attachments">Please provide any attachments that may provide more context into the issues on your account</label> 
     <div id="dropzone-placeholder-div" style="" class=""> 
      <div style="position: relative; width: 100%; height: 100%"> 
       <div id="sendsafely-iframe" style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; z-index: 10; opacity: 0.01;"> 
        <iframe src="https://static-secure.instacart.com/html/dropzone.html" scrolling="no" style="width: 100%; height: 100%;"></iframe> 
       </div> 
       <div id="sendsafely-dropzone" style="position: absolute; top: 0; left: 0; width: 100%; height:100%; overflow: hidden; position: relative; z-index: 1;"> 
        <div style="width: 100%; border: 2px dashed #F3F3F3; border-color: rgba(0,0,0,0.05); font-size: 14px; text-align: center; padding-top: 10px; padding-bottom: 10px;; color: #666666; background-color: #ffffff -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box;" align="center"> 
         <div style="margin: 0 auto; float:center; min-width: 45%; max-width: 95%; display: inline-block;"> 
          <span><img src="https://app-static.sendsafely.com/images/external/logo.png" width="23px" height="23px" style="margin-right:5px; margin-top: -2px;vertical-align: middle;"></span> 
          <span>Drag files here or click to add a file</span> 
         </div> 
        </div> 
       </div> 
      </div> 
      <div> 
       <ul id="sendsafely-attached-file-list" style="margin: 0; overflow: hidden; padding: 0;"></ul> 
      </div> 
      <div id="sendsafely-error-message" class="alert alert-dismissible" role="alert" style="display:none; margin-top:5px; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box;"></div> 
     </div> 
    </div> 
    <input type="submit" value="SUBMIT EMAIL TO: " secure_exooutsider01@yahoo.com"="" <a="" href="mailto: secure_eXoOutsider01@yahoo.com"> 
   </form> 
   <script>
  $("#issue_selector").change(() => {
    $("#secure_issue").val($("#issue_selector").val())
  })
</script> 
  </div> 
 </body>
</html>
