function calculateDraw() {
  const myCanvas = document.querySelector("#myCanvas");
  const painter = myCanvas.getContext("2d");
  const w = document.querySelector("#width");
  const h = document.querySelector("#height");
  const x = document.querySelector("#Px");
  const y = document.querySelector("#Py");
  painter.fillStyle = "blue";
  painter.fillRect(w.value, h.value, x.value, y.value);
}

function clearCanvas() {
  const myCanvas = document.querySelector("#myCanvas");
  const painter = myCanvas.getContext("2d");
  painter.clearRect(0, 0, 300, 300);
}

function onWindowLoad() {
  const btn = document.querySelector("#btn1");
  btn.onclick = calculateDraw;
  const btn2 = document.querySelector("#btn2");
  btn2.onclick = clearCanvas;
}
