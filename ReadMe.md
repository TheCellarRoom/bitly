###### Bitly


> get Bit.ly short url with cURL with this class.

###### Usage

    <?php
    // include class
    include('class.Bitly.php');
    // have some url
    $url	  = 'http://www.google.co.uk';
    // instantiate class with your API username and key
    $class  = new getBitly('token');
    // pass the class your url to the method, get the short one back
    $return = $class->getUrl('$url');
    // print it d'uh
    print $return;
    ?>
    
