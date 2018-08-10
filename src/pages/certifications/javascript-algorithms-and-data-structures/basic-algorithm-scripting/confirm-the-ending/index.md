
function confirmEnding(str, target) {
  // "Never give up and good luck will find you."
  // -- Falcor
  var longT = target.length;
  var last = str.substr(str.length - longT);
  if(last==target){
    return true
  }
  else{
    return false;
  }
}

confirmEnding("Bastian", "n");
