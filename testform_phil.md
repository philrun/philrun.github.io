---
layout: page
title: Phil Rogers
tagline: Dartford, trains, tech, stuff
---
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>

{% include JB/setup %}

<div class="container">
<form id="localStorageTest" method="post" action="http://www.southeasternrailway.co.uk/contact/contact-us-form">


	<div class="col-md-9">
	
    	<div class="row">
       		<div class="col-md-3">
    			<label>Title:</label>
         	</div>
         	
        	<div class="col-md-9">
        		<select name="title">
        		<option value="Mr">Mr</option>
        		<option value="Ms">Ms</option>
        		<option value="Miss">Miss</option>
        		<option value="Mrs">Mrs</option>
        		<option value="Dr">Dr</option>
        		<option value="Other">Other</option>
        		</select>
    		</div>
    	</div>

    	<div class="row">
       		<div class="col-md-3">
    			<label>Surname:</label>
         	</div>
        	<div class="col-md-9">
    			<input type="text" name="surname" id="surname" class="stored" value="" />
    		</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Email:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="email" name="email" id="email" class="stored" value="" />
			</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Message:</label>
    		</div>
        	<div class="col-md-9">		
   		 		<textarea name="yourcomments" id="yourcomments" class="stored"></textarea>
			</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    		</div>
        	<div class="col-md-9">		
    			<input type="submit" class="demo-button" value="Submit" />
    		</div>
    	</div>
      	<div class="row">
    		These fields are related to your journey. These are autofilled with your typical journey based on time of day. If your comment is train specific, you should fill this out to give Southeastern info about your journey.
    	</div>  	
     	<div class="row">
       		<div class="col-md-3">
       			<label>Departure station:</label>
    		</div>
        	<div class="col-md-9">		
    			This needs to be an auto-complete text field (for mobile)
    			<select name="depstation">
    			<option value="ABW" >Abbey Wood</option> 
<option value="ADM" >Adisham</option> 
<option value="AYP" >Albany Park</option> 
<option value="AFK" >Ashford Intl</option> 
<option value="AYL" >Aylesford</option> 
<option value="AYH" >Aylesham</option> 
<option value="BMG" >Barming</option> 
<option value="BNH" >Barnehurst</option> 
<option value="BBL" >Bat &amp; Ball</option> 
<option value="BAT" >Battle</option> 
<option value="BSD" >Bearsted</option> 
<option value="BEC" >Beckenham Hill</option> 
<option value="BKJ" >Beckenham Junction</option> 
<option value="BKS" >Bekesbourne</option> 
<option value="BGM" >Bellingham</option> 
<option value="BEG" >Beltring</option> 
<option value="BVD" >Belvedere</option> 
<option value="BXY" >Bexley</option> 
<option value="BXH" >Bexleyheath</option> 
<option value="BKL" >Bickley</option> 
<option value="BCH" >Birchington-on-Sea</option> 
<option value="BKH" >Blackheath</option> 
<option value="BRG" >Borough Green &amp; Wrotham</option> 
<option value="BRX" >Brixton</option> 
<option value="BSR" >Broadstairs</option> 
<option value="BMN" >Bromley North</option> 
<option value="BMS" >Bromley South</option> 
<option value="CBE" >Canterbury East</option> 
<option value="CBW" >Canterbury West</option> 
<option value="CTF" >Catford</option> 
<option value="CFB" >Catford Bridge</option> 
<option value="CHG" >Charing</option> 
<option value="CTN" >Charlton</option> 
<option value="CRT" >Chartham</option> 
<option value="CTM" >Chatham</option> 
<option value="CLD" >Chelsfield</option> 
<option value="CSW" >Chestfield &amp; Swalecliffe</option> 
<option value="CIL" >Chilham</option> 
<option value="CIT" >Chislehurst</option> 
<option value="CTK" >City Thameslink</option> 
<option value="CLK" >Clock House</option> 
<option value="CRY" >Crayford</option> 
<option value="CFT" >Crofton Park</option> 
<option value="CWU" >Crowhurst</option> 
<option value="CUX" >Cuxton</option> 
<option value="DFD" >Dartford</option> 
<option value="DEA" >Deal</option> 
<option value="DMK" >Denmark Hill</option> 
<option value="DEP" >Deptford</option> 
<option value="DVP" >Dover Priory</option> 
<option value="DMP" >Dumpton Park</option> 
<option value="DNG" >Dunton Green</option> 
<option value="EFL" >East Farleigh</option> 
<option value="EML" >East Malling</option> 
<option value="EBD" >Ebbsfleet Intl</option> 
<option value="EDN" >Eden Park</option> 
<option value="EPH" >Elephant &amp; Castle</option> 
<option value="ELE" >Elmers End</option> 
<option value="ESD" >Elmstead Woods</option> 
<option value="ELW" >Eltham</option> 
<option value="ERH" >Erith</option> 
<option value="ETC" >Etchingham</option> 
<option value="EYN" >Eynsford</option> 
<option value="FCN" >Falconwood</option> 
<option value="FNR" >Farningham Road</option> 
<option value="ZFD" >Farringdon</option> 
<option value="FAV" >Faversham</option> 
<option value="FKC" >Folkestone Central</option> 
<option value="FKW" >Folkestone West</option> 
<option value="FRT" >Frant</option> 
<option value="GLM" >Gillingham (Kent)</option> 
<option value="GRV" >Gravesend</option> 
<option value="GNH" >Greenhithe</option> 
<option value="GNW" >Greenwich</option> 
<option value="GRP" >Grove Park</option> 
<option value="HAI" >Halling</option> 
<option value="HRM" >Harrietsham</option> 
<option value="HGS" >Hastings</option> 
<option value="HYS" >Hayes</option> 
<option value="HCN" >Headcorn</option> 
<option value="HNB" >Herne Bay</option> 
<option value="HNH" >Herne Hill</option> 
<option value="HIB" >High Brooms</option> 
<option value="HGM" >Higham</option> 
<option value="HLB" >Hildenborough</option> 
<option value="HGR" >Hither Green</option> 
<option value="HBN" >Hollingbourne</option> 
<option value="KSN" >Kearsney</option> 
<option value="KMS" >Kemsing</option> 
<option value="KML" >Kemsley</option> 
<option value="KTH" >Kent House</option> 
<option value="KDB" >Kidbrooke</option> 
<option value="KCK" >Knockholt</option> 
<option value="LAD" >Ladywell</option> 
<option value="LEE" >Lee</option> 
<option value="LEN" >Lenham</option> 
<option value="LEW" >Lewisham</option> 
<option value="BFR" >London Blackfriars</option> 
<option value="LBG" >London Bridge</option> 
<option value="CST" >London Cannon Street</option> 
<option value="CHX" >London Charing Cross</option> 
<option value="STP" >London St Pancras Intl</option> 
<option value="VIC" >London Victoria</option> 
<option value="WAE" >London Waterloo East</option> 
<option value="LGF" >Longfield</option> 
<option value="LGJ" >Loughborough Junction</option> 
<option value="LSY" >Lower Sydenham</option> 
<option value="MDB" >Maidstone Barracks</option> 
<option value="MDE" >Maidstone East</option> 
<option value="MDW" >Maidstone West</option> 
<option value="MRN" >Marden</option> 
<option value="MAR" >Margate</option> 
<option value="MTM" >Martin Mill</option> 
<option value="MZH" >Maze Hill</option> 
<option value="MEP" >Meopham</option> 
<option value="MSR" >Minster</option> 
<option value="MTG" >Mottingham</option> 
<option value="NBC" >New Beckenham</option> 
<option value="NWX" >New Cross</option> 
<option value="NEH" >New Eltham</option> 
<option value="NHE" >New Hythe</option> 
<option value="NGT" >Newington</option> 
<option value="NFL" >Northfleet</option> 
<option value="NHD" >Nunhead</option> 
<option value="ORE" >Ore</option> 
<option value="ORP" >Orpington</option> 
<option value="OTF" >Otford</option> 
<option value="PDW" >Paddock Wood</option> 
<option value="PMR" >Peckham Rye</option> 
<option value="PNE" >Penge East</option> 
<option value="PET" >Petts Wood</option> 
<option value="PLC" >Pluckley</option> 
<option value="PLU" >Plumstead</option> 
<option value="QBR" >Queenborough</option> 
<option value="RAI" >Rainham</option> 
<option value="RAM" >Ramsgate</option> 
<option value="RVB" >Ravensbourne</option> 
<option value="RBR" >Robertsbridge</option> 
<option value="RTR" >Rochester</option> 
<option value="RYE" >Rye</option> 
<option value="SDG" >Sandling</option> 
<option value="SDW" >Sandwich</option> 
<option value="SEG" >Selling</option> 
<option value="SEV" >Sevenoaks</option> 
<option value="SSS" >Sheerness on Sea</option> 
<option value="SPH" >Shepherds Well</option> 
<option value="SEH" >Shoreham</option> 
<option value="SRT" >Shortlands</option> 
<option value="SID" >Sidcup</option> 
<option value="SIT" >Sittingbourne</option> 
<option value="SGR" >Slade Green</option> 
<option value="SDA" >Snodland</option> 
<option value="SWO" >Snowdown</option> 
<option value="SOR" >Sole Street</option> 
<option value="SAJ" >St Johns</option> 
<option value="SLQ" >St Leonards Warrior Square</option> 
<option value="SMY" >St Mary Cray</option> 
<option value="SPU" >Staplehurst</option> 
<option value="SCG" >Stone Crossing</option> 
<option value="SOG" >Stonegate</option> 
<option value="SFA" >Stratford Intl</option> 
<option value="SOO" >Strood</option> 
<option value="STU" >Sturry</option> 
<option value="SUP" >Sundridge Park</option> 
<option value="SWL" >Swale</option> 
<option value="SAY" >Swanley</option> 
<option value="SWM" >Swanscombe</option> 
<option value="SYH" >Sydenham Hill</option> 
<option value="TEY" >Teynham</option> 
<option value="TON" >Tonbridge</option> 
<option value="TBW" >Tunbridge Wells</option> 
<option value="WAD" >Wadhurst</option> 
<option value="WAM" >Walmer</option> 
<option value="WTR" >Wateringbury</option> 
<option value="WLI" >Welling</option> 
<option value="WDU" >West Dulwich</option> 
<option value="WMA" >West Malling</option> 
<option value="WLD" >West St Leonards</option> 
<option value="WWI" >West Wickham</option> 
<option value="WCB" >Westcombe Park</option> 
<option value="WHA" >Westenhanger</option> 
<option value="WGA" >Westgate on Sea</option> 
<option value="WHI" >Whitstable</option> 
<option value="WWA" >Woolwich Arsenal</option> 
<option value="WWD" >Woolwich Dockyard</option> 
<option value="WYE" >Wye</option> 
<option value="YAL" >Yalding</option> 
</select>
    		</div>
    	</div>   	
    	
    	<div class="row">
    		These fields aren't required on the Southeastern website, however if you want to, you can fill them out
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>First name:</label>
         	</div>
        	<div class="col-md-9">
    			<input type="text" name="forenames" id="forenames" class="stored" value="" />
    		</div>
    	</div>
    	<div class="row">
       		<div class="col-md-3">
    			<label>Address Line 1:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="address1" name="address1" id="address1" class="stored" value="" />
			</div>
    	</div>  
    	<div class="row">
       		<div class="col-md-3">
    			<label>Address Line 2:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="address2" name="address2" id="address2" class="stored" value="" />
			</div>
    	</div>      	
    	<div class="row">
       		<div class="col-md-3">
    			<label>Town/City:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="city" name="city" id="city" class="stored" value="" />
			</div>
    	</div>      
    	<div class="row">
       		<div class="col-md-3">
    			<label>Postcode:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="postcode" name="postcode" id="postcode" class="stored" value="" />
			</div>
    	</div>     	
    	<div class="row">
       		<div class="col-md-3">
    			<label>County:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="county" name="county" id="county" class="stored" value="" />
			</div>
    	</div>      	
    	<div class="row">
       		<div class="col-md-3">
    			<label>Telephone:</label>
    		</div>
        	<div class="col-md-9">	
    			<input type="telephone" name="telephone" id="telephone" class="stored" value="" />
			</div>
    	</div>       		  	
	</div>
</form>
    <div class="col-md-3">

    	<a class="twitter-timeline" href="https://twitter.com/philmonkey" data-widget-id="470916039635517440">Tweets by @philmonkey</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>



    </div>



<script type="text/javascript">
$(document).ready(function () {
    function init() {
        if (localStorage["title"]) {
            $('#title').val(localStorage["title"]);
        }
        if (localStorage["surname"]) {
            $('#surname').val(localStorage["surname"]);
        }        
        if (localStorage["email"]) {
            $('#email').val(localStorage["email"]);
        }
        
        //useful fields (journey related):
        if (localStorage["depstation"]) {
            $('#depstation').val(localStorage["depstation"]);
        }       
        
        //optional fields:
        if (localStorage["forenames"]) {
            $('#forenames').val(localStorage["forenames"]);
        }
        if (localStorage["address1"]) {
            $('#address1').val(localStorage["address1"]);
        }
        if (localStorage["address2"]) {
            $('#address2').val(localStorage["address2"]);
        }
        if (localStorage["city"]) {
            $('#city').val(localStorage["city"]);
        }
        if (localStorage["postcode"]) {
            $('#postcode').val(localStorage["postcode"]);
        }
        if (localStorage["county"]) {
            $('#county').val(localStorage["county"]);
        }
        if (localStorage["telephone"]) {
            $('#telephone').val(localStorage["telephone"]);
        }     
		if (localStorage["yourcomments"]) {
            $('#yourcomments').val(localStorage["yourcomments"]);
        }
    }
	init();
});

$('.stored').change(function () {
    localStorage[$(this).attr('name')] = $(this).val();
});
	
$('#localStorageTest').submit(function() {
	//localStorage.clear();
});
</script>
<script type="text/javascript">
(function( win ){
	var doc = win.document;
   	
	// If there's a hash, or addEventListener is undefined, stop here
	if( !location.hash && win.addEventListener ){
		//scroll to 1
		window.scrollTo( 0, 1 );
		var scrollTop = 1,
			getScrollTop = function(){
				return win.pageYOffset || doc.compatMode === "CSS1Compat" && doc.documentElement.scrollTop || doc.body.scrollTop || 0;
			},
			//reset to 0 on bodyready, if needed
			bodycheck = setInterval(function(){
				if( doc.body ){
					clearInterval( bodycheck );
					scrollTop = getScrollTop();
					win.scrollTo( 0, scrollTop === 1 ? 0 : 1 );
				}	
			}, 15 );
		win.addEventListener( "load", function(){
			setTimeout(function(){
					//reset to hide addr bar at onload
					win.scrollTo( 0, scrollTop === 1 ? 0 : 1 );
			}, 0);
		} );
	}
})( this );
</script>        