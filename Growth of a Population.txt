function nbYear(p0, percent, aug, p, years = 0) {
  return p0 >= p
    ? years
    : nbYear(
        Math.floor(p0 + p0 * (percent / 100)) + aug,
        percent,
        aug,
        p,
        years + 1
      );
}