# js-
var fir={flag:true};  var test=!!fir.flag;//等效于var test=fir.flag||false;  alert(test);  由于对null与undefined用!操作符时都会产生true的结果， 所以用两个感叹号的作用就在于， 如果明确设置了fir中flag的值（非 null/undefined/0/""/等值），自然test就会取跟o.flag一样的值； 如果没有设置，test就会默认为false，而不是 null或undefined。
