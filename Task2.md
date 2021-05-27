# Task 2

#### 1. Make the code below cleaner, better and reusable

```php
# Add leading 0 number
# ex: 5 => 0005
private function convertNumber($number) {
    for ($i = 1; $i <= strlen($number); $i++) {
      if (strlen($number) === $i) {
         $number = sprintf("%04d", $number);
         return $number;
      }
   }
}

convertNumber(5);
```

#### 2. After change the code, make a pull request
