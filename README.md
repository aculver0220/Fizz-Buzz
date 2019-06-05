for (var x = 0; x < 101; x++) {
    if (x % 15 === 0) {
      console.log("Fizzbuzz");
    }
    if (x % 3 === 0) {
        console.log("Fizz");
    }
    else if (x % 5 === 0) {
        console.log("Buzz");
    }
    else {
        console.log(x);
    }
}
