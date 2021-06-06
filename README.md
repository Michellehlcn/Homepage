# Homepage
This libraries collects all my work which were a variety of short-term projects for my clients and my personal research.
<div class="wrap">
  <div class="container">
    <div class="row">
      <div class="twelve columns">
        <h4>Filter Programmes</h4>
      </div>
    </div><!-- end of row -->

    <div class="row">
      <div class="twelve columns">
        <div class="programs">
          <button class="filter-btn" data-filter="all">All</button>
          <button class="filter-btn" data-filter=".undergraduate">Undergraduate</button>
          <button class="filter-btn" data-filter=".graduate">Graduate</button>
          <button class="filter-btn" data-filter=".phd">PhD</button>
        </div>
      </div>
    </div><!-- end of row -->

    <div class="row">
      <div class="columns twelve">
        <h4>Sort Programmes</h4>
      </div>
    </div><!-- end of row -->

    <div class="row">
      <div class="columns twelve">
        <div class="programs">
          <button class="sort-btn" data-sort="default:asc">Default</button>
          <button class="sort-btn" data-sort="random">Random</button>
          <button class="sort-btn" data-sort="order:asc">Ascending</button>
          <button class="sort-btn" data-sort="year:desc order:desc">Descending<span class="multi">(Multi)</span></button>
        </div>
      </div>
    </div><!-- end of row -->

    <div class="row">
      <div class="twelve columns">
        <h4>Programmes List</h4>
      </div>
    </div><!-- end of row -->

    <div class="row">
      <div class="twelve columns">
        <ul class="courses" id="mix-wrapper">
          <li class="mix-target undergraduate" data-order="5" data-year="4"><a href="#">Economics<span>(U)</span></a></li>
          <li class="mix-target graduate" data-order="14" data-year="2"><a href="#">Pharmacology<span>(G)</span></a></li>
          <li class="mix-target graduate" data-order="7" data-year="1"><a href="#">Informatics<span>(G)</span></a></li>
          <li class="mix-target phd" data-order="4" data-year="3"><a href="#">Criminology<span>(P)</span></a></li>
          <li class="mix-target undergraduate" data-order="16" data-year="3"><a href="#">Sociology<span>(U)</span></a></li>
          <li class="mix-target undergraduate" data-order="6" data-year="4"><a href="#">Greek<span>(U)</span></a></li>
          <li class="mix-target phd" data-order="1" data-year="3"><a href="#">Astrophysics<span>(P)</span></a></li>
          <li class="mix-target undergraduate" data-order="12" data-year="4"><a href="#">Nursing<span>(U)</span></a></li>
          <li class="mix-target undergraduate" data-order="10" data-year="5"><a href="#">Microbiology<span>(U)</span></a></li>
          <li class="mix-target undergraduate" data-order="9" data-year="4"><a href="#">Mathematics<span>(U)</span></a></li>
          <li class="mix-target graduate" data-order="11" data-year="3"><a href="#">Nanoscience<span>(G)</span></a></li>
          <li class="mix-target phd" data-order="2" data-year="2"><a href="#">Biochemistry<span>(P)</span></a></li>
          <li class="mix-target phd" data-order="13" data-year="3"><a href="#">Pathology<span>(P)</span></a></li>
          <li class="mix-target graduate" data-order="8" data-year="1"><a href="#">Management<span>(G)</span></a></li>
          <li class="mix-target graduate" data-order="3" data-year="2"><a href="#">Biostatistics<span>(G)</span></a></li>
          <li class="mix-target phd" data-order="15" data-year="4"><a href="#">Public Health<span>(P)</span></a></li>
        </ul>
      </div>
    </div><!-- end of row -->   
  </div><!-- end of container -->
</div><!-- end of wrap -->

<footer>
  <p class="p">Demo by George Martsoukos.</p>
</footer>

@import url(https://fonts.googleapis.com/css?family=Alegreya+Sans+SC);

body {
	background: #ededed;
	font-family: 'Alegreya Sans SC', sans-serif;
}

h4 {
	font-size: 21px;
	border-radius: 5px;
	margin: 0 auto;
	text-align: center;
	background: #d2d2d2;
	color: white;
	font-weight: 700;
	padding: 3px 0;
}

li {
	margin: 0;
}

a {
	font-size: 18px;
	text-decoration: none;
}

span {
	display: block;
	font-size: .75em;
	font-style: italic;
	position: relative;
	top: 5px;
}

.multi {
	display: inline;
	top: 0;
	left: 3px;
}

img {
	max-width: 100%;
}

.programs,
.courses {
	margin: 8px 0 0 0;
}

.programs {
	font-size: 0;
	margin-bottom: 15px;
}

.programs button {
	outline: none;
	margin-bottom: 0;
	background: whitesmoke;
	width: 50%;
	height: auto;
	font-weight: normal;
	border: 1px solid #ededed;
	color: #000000;
	font-size: 14px;
	padding: 4px 0;
	text-shadow: 0px 0px 0px #2f6627;
}

.programs button:hover {
	background: #99cfe0;
}

.programs button.active {
	box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.5) inset, 0px 0px 1px transparent;
	background: #3a9fbf;
	color: white;
}

.courses {
	margin-bottom: 15px;
	font-size: 0;
	background: whitesmoke;
}

.courses li {
	text-align: center;
	font-size: 14px;
	display: inline-block;
	width: 46%;
	margin: 0 2%;
}

.courses a {
	display: block;
	height: 60px;
	margin: 15px 0;
	padding-top: 12.5px;
	background: whitesmoke;
	color: black;
	border: 1px solid white;
	-webkit-transition: all .4s ease;
	        transition: all .4s ease;
}

.courses a:hover {
	background: #99cfe0;
}

.courses .mix-target {
	display: none;
}

.p, .p a {
  font-family: Arial, sans-serif;
  font-size: 14px;
  text-align: center;
}


/* MEDIA QUERIES STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */

@media only screen and (min-width: 750px) {

	.container {
		width: 95%;
	}

	.courses a {
		background: #EBEBEB;
		border: none;
	}

	.courses a:hover {
		background: #EBEBEB;
		-webkit-transform: scale(1.15);
		    -ms-transform: scale(1.15);
		        transform: scale(1.15);
	}

	h4 {
		width: 50%;
		margin-top: 12px;
	}

	img {
		margin-bottom: 0;
	}

	.programs {
		margin-bottom: 0;
	}

	.programs button {
		width: 25%;
		margin-bottom: 15px;
	}

	.courses li {
		width: 21%;
	}

}
$('#mix-wrapper').mixItUp({
  load: {
  	sort: 'order:asc'
  },
	animation: {
    effects: 'fade rotateZ(-180deg)',
    duration: 700
  },
  selectors: {
    target: '.mix-target',
    filter: '.filter-btn',
    sort: '.sort-btn'
  },
  callbacks: {
    onMixEnd: function(state){
      console.log(state)
    }
  }
});
