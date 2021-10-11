# chartjs2-round-top-bar

##Angular 2 4 5 6 7 8 9

npm i chartjs2-round-top-bar

import 'chartjs2-round-top-bar';

new Chart('barChart', {
        type: 'bar',
        //Border radius; Default: 0; If a negative value is passed, it will overwrite to 0;
        cornerRadius: 10, 
        //Default: false; if true, this would round all corners of final box;
        fullCornerRadius: false, 
        //Default: false; if true, th
        data: {
          labels: ['label 1'],
          datasets: [{label: 'Label 1', data}]}
 });
