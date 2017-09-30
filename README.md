# PHP-function


php 7

type hinting ( string , int, bool  )


declare(strict_types = 1); ye strict mode hai jo string to int main automatiacley convert honey say rokta hai
2)
return type declaration
ab ye function array value he return karega
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

