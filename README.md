# dz20_11.03

Це ladder (сходи) – об'єкт, який дозволяє підніматися вгору та спускатися:

let ladder = {
step: 0,
up: function () {
this.step++;
},
down: function () {
this.step--;
},
showStep: function () { // показывает текущую ступеньку
alert(this.step);
}
};
