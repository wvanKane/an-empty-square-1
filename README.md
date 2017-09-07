# an-empty-square-1
# 最简单的想法，但却最复杂
##
var s = window.prompt('Enter size of the square');
/* convert the input string into a number */
var n = parseInt(s);
/* build a line with n stars */
var line1 = '';
var line2 = '* ';
for (var i=0; i<n; i++) { line1 = line1 + '* '; }
for (var i=1; i<n-1; i++) { line2 = line2 + '  '; }
line2 = line2 + '* ';
/* build a square with n lines */
var sqr = '';
sqr = sqr + line1 + '\n';
for (i=1; i<n-1; i++) { sqr = sqr + line2 + '\n';}
if (n > 1 ) {sqr = sqr + line1 + '\n';}
console.log(sqr);
##
