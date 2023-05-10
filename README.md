# parallex-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>parallax website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section class="pimg1">
      <div class="ptext">
        <span class="textBg">
            parallax website
        </span>
      </div>
    </section>
    <section class="section section-light">
        <h2>section one</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde voluptatum nihil aperiam quae, esse pariatur dolores natus obcaecati debitis veritatis eligendi aut laboriosam, quidem, quaerat aliquid deserunt corrupti. Fugiat a blanditiis, id molestias tempora sunt unde reprehenderit enim quam! Consectetur deleniti commodi, aliquam ipsam labore rem obcaecati maxime ipsum nostrum architecto natus, ducimus ratione. Debitis sit doloremque eaque iste totam sunt nulla. Dolores, nihil voluptatibus! Sapiente molestias neque perspiciatis cupiditate fugit quo officia repellat voluptas sed, quas voluptate harum, asperiores reiciendis laborum eaque necessitatibus, beatae hic. Sunt dolorem praesentium dignissimos architecto debitis, temporibus commodi esse tempora quidem assumenda necessitatibus hic.</p>
    </section>
    <section class="pimg2">
        <div class="ptext">
          <span class="textBg">
              Explore Nature
          </span>
        </div>
      </section>
      <section class="section section-dark">
        <h2>section two</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde voluptatum nihil aperiam quae, esse pariatur dolores natus obcaecati debitis veritatis eligendi aut laboriosam, quidem, quaerat aliquid deserunt corrupti. Fugiat a blanditiis, id molestias tempora sunt unde reprehenderit enim quam! Consectetur deleniti commodi, aliquam ipsam labore rem obcaecati maxime ipsum nostrum architecto natus, ducimus ratione. Debitis sit doloremque eaque iste totam sunt nulla. Dolores, nihil voluptatibus! Sapiente molestias neque perspiciatis cupiditate fugit quo officia repellat voluptas sed, quas voluptate harum, asperiores reiciendis laborum eaque necessitatibus, beatae hic. Sunt dolorem praesentium dignissimos architecto debitis, temporibus commodi esse tempora quidem assumenda necessitatibus hic.</p>
    </section>
    <section class="pimg3">
        <div class="ptext">
          <span class="textBg">
              look, deep into nature
          </span>
        </div>
      </section>
      <section class="section section-dark">
        <h2>section three</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde voluptatum nihil aperiam quae, esse pariatur dolores natus obcaecati debitis veritatis eligendi aut laboriosam, quidem, quaerat aliquid deserunt corrupti. Fugiat a blanditiis, id molestias tempora sunt unde reprehenderit enim quam! Consectetur deleniti commodi, aliquam ipsam labore rem obcaecati maxime ipsum nostrum architecto natus, ducimus ratione. Debitis sit doloremque eaque iste totam sunt nulla. Dolores, nihil voluptatibus! Sapiente molestias neque perspiciatis cupiditate fugit quo officia repellat voluptas sed, quas voluptate harum, asperiores reiciendis laborum eaque necessitatibus, beatae hic. Sunt dolorem praesentium dignissimos architecto debitis, temporibus commodi esse tempora quidem assumenda necessitatibus hic.</p>
    </section>
</body>
  </html>
  <style>
  html,
body{
    height: 100%;
    margin: 0;
    font-size: 16px;
    font-family: "lato", sans-serif;
    font-weight: 400;
    line-height: 1.8em;
    color: black;
}
.pimg1{
    background-image: url("image1.png");
    min-height: 100%;
}
.pimg2{
    background-image: url("image2.png");
    min-height: 400px;
}
.pimg3{
    background-image: url("image3.png");
    min-height: 400px;
}
.pimg1, .pimg2, .pimg3{
    position: relative;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
} 
.ptext{
    position: absolute;
    top: 50%;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 27px;
    letter-spacing: 8px;
    text-transform: uppercase;
}
.textBg{
    background-color: #313534;
    color: white;
    padding: 20px;
}
.section{
    padding: 50px 80px;
    text-align: center;

}
.section-light{
    background-color:  #fff;
    color: #666;
}
.section-dark{
    background-color: #282e34;
    color: #ddd;
}

    </style>
