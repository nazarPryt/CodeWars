function isPangram(string){
  const alphabet = 'abcdefghijklmnopqrstuvwxyz';
  const str = string.toLowerCase();
  
  for (let i = 0; i < alphabet.length-1; i += 1) {
    if (str.indexOf(alphabet[i]) === -1) {
      return false;
    }
  }
  
  return true;
}