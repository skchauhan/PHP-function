# PHP-function

php 7

1)
type hinting ( string , int, bool  )

declare(strict_types = 1); 


2)

function test() : array {
return array();
}
test();

3)
Null coalesece operator
$name = isset($nm) ? $nm : 'Not found';
now we can use 
$name = $nm ?? 'not found'

4)
group Imports & namespaces
with the use keyword we can import multiple 
namespace  country{
	class  india {
	}
	class  pakistan {
	}
}
namespace Counry\state {
	class  punjab{
	}
}
namespace App {
use Country\{india,pakistan, state\punjab }
var_dump(new India);
}

5)
SPACESHIP OPERATOR  / combined comparison
$a <=> $b
if a is grater than b return 1
if a is less than b return -1
if a is equal b return 0



6)
Php error log in txt file

ini_set("log_errors", 1);
ini_set("error_log", "php-error.log");
echo $adfdsf;



