# chartjs-top-round-bar

##Angular 2 4 5 6 7 8 9

npm i chartjs-top-round-bar

import 'chartjs-top-round-bar';

new Chart('barChart', {
        type: 'roundedBar',
        data: {
          labels: ['label 1'],
          datasets: [{label: 'Label 1', data}]},
        options: { barRoundness: 0.3}
        
 });
