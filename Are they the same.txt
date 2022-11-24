const comp = (a1, a2) => {
  if (!a1 || !a2 || a1.length !== a2.length) return false;
  return a1.map(x => x * x).sort().toString() === a2.sort().toString();
}