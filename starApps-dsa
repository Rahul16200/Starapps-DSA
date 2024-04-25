const getMinimumPlaneCount = (inputArr) => {
  let planeCounter = 0;
  let positon = inputArr[0];

  for (let i = 1; i < inputArr.length; i++) {
    if (positon === 0) {
      return -1;
    }
    if (positon < i) {
      planeCounter++;
      positon = inputArr[i];
    } else {
      positon = Math.max(positon, inputArr[i]);
    }
  }
  return planeCounter;
};
