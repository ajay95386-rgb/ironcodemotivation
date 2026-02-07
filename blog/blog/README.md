<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>IronCode Motivation | Nutrition & Fitness Blog</title>
<meta name="description" content="Daily nutrition, calories, protein breakdown and fat loss guides by IronCode Motivation.">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body style="background:#0b0b0b;color:#fff;font-family:Arial;padding:30px">

<h1>IronCode Motivation Blog</h1>
<p>Daily nutrition, calories & fitness science.</p>

<div style="background:#111;padding:20px;border-radius:10px;margin-bottom:20px">
<h2>🔥 Today’s Nutrition Guide</h2>
<a id="dailyBlog" href="#" style="color:#00c853;font-size:18px">
Read today’s article →
</a>
</div>

<h2>All Articles</h2>

<ul>
<li><a href="blog/oats-calories-fat-loss.html">Oats: Calories & Fat Loss</a></li>
<li><a href="blog/eggs-protein-fat-loss.html">Eggs: Protein & Nutrition</a></li>
<li><a href="blog/banana-workout-energy.html">Banana: Workout Energy</a></li>
</ul>

<script>
const blogs=[
"oats-calories-fat-loss.html",
"eggs-protein-fat-loss.html",
"banana-workout-energy.html"
];
const random=Math.floor(Math.random()*blogs.length);
document.getElementById("dailyBlog").href="blog/"+blogs[random];
</script>

</body>
</html>
