# WorkingWithStrings
Mod 2 Sec 6

function textNormalizer(text) {
  return `${text.toLowerCase() } ${text.trim()}`;
}

/* From here down, you are not expected to 
   understand.... for now :)  
   
   
   Nothing to see here!
   
*/

// tests

function testTextNormalizer() {
  const text = "   let's GO SURFING NOW everyone is learning how   ";
  const expected = "let's go surfing now everyone is learning how";
  if (textNormalizer(text) === expected) {
    console.log('SUCCESS: `textNormalizer` is working');
  } else {
    console.log('FAILURE: `textNormalizer` is not working');
  }
}

testTextNormalizer();
