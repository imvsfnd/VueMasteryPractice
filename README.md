# Init

- HTML
    <code>
    	<div id="app">
       		<h1>{{ product }}</h1>
   		</div>
    </code>		
- JS
	var app = new Vue ({
		el: '#app',
		data: {
			product: 'Socks'
		}
	})		