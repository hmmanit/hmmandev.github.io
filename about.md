---
layout: about
title: About
image: assets/images/about.webp
nav-menu: true

---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>About</h1>
		</header>

<!-- Elements -->
<h2 id="elements">Skills</h2>
<div class="row 200%">
	<div class="8u 12u$(medium)">

<div class="table-wrapper">
	<table>
		<thead>
			<tr>
				<th>Android Jetpack</th>
				<th>3rd party libraries</th>
				<th>Others</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>ViewModel</td>
				<td>Material components</td>
				<td>Clean Architecture</td>
			</tr>
			<tr>
				<td>LiveData</td>
				<td>Retrofit</td>
				<td>UI design</td>
			</tr>
			<tr>
				<td>Navigation</td>
				<td>Glide - Coil</td>
				<td>Dark & Light themes supporting</td>
			</tr>
			<tr>
				<td>Lifecycles</td>
				<td>RxJava - Android</td>
				<td>Multiple screen sizes supporting</td>
			</tr>
			<tr>
				<td>Data Binding</td>
				<td>Kotlin Coroutines</td>
				<td></td>
			</tr>
            <tr>
				<td>Room</td>
				<td></td>
				<td></td>
			</tr>
            <tr>
				<td>Animation & Transitions</td>
				<td></td>
				<td></td>
			</tr>
            <tr>
				<td>Hilt</td>
				<td></td>
				<td></td>
			</tr>
            <tr>
				<td>Compose</td>
				<td></td>
				<td></td>
			</tr>
		</tbody>
	</table>
</div>

</div>
<div class="4u 12u$(medium)">

<h2>Personal info</h2>
Full name: <b>Man Ho Minh</b> <br/>
DOB: <b>1996 July 20</b> <br/>
Gender: <b>Male</b> <br/>
Email: <b><a href="mailto:{{ site.email }}">{{ site.email }}</a></b> <br/>

<br/>

<ul class="icons">
    {% for key_value in site.socials %}
        {% if key_value[1] %}
            <li>
                <a href="{{ key_value[1] }}" class="icon alt fa-{{ key_value[0] | downcase }}" target="_blank" rel="noopener noreferrer" aria-label="{{ key_value[0] }}">
                    <span class="label">{{ key_value[0] }}</span>
                </a>
            </li>
        {% endif %}
    {% endfor %}
</ul>

<h2>Education</h2>
<b>CAN THO UNIVERSITY</b> <br/>
Sep 2015 – Sep 2019 <br/>
Major: <b>Information Technology</b> <br/>
GPA: <b>3.11/4.00</b> <br/>

</div>
</div>

</div>
</section>

</div>
