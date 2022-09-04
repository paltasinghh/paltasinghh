<!DOCTYPE html>
<html>
<head>
    <title>Register</title>
    <link rel="stylesheet" href="Register.css">
    <link href="https://fonts.googleapis.com/css?family=Poppins" rel="stylesheet">
</head>

<body>
   
    <h1 class="main-head">
        Blood Donation Camp
    </h1>
    <div class="image">
            <img src="bloodd.png" height="350px">
    </div>
        <div class="box">
            <form>
                <h3 class="head">Register</h3>
                <label>Name :</label>
                <br>
                <input type="text" pattern="[a-zA-Z'-'\s]*" class="name" maxlength="40" placeholder="Enter your name">
                <br>

                <label>Gender :</label>
                <br>
                <label for="101">
                <input type="radio" value="male" name="class" id="101">
                Male
                </label>

                <span class="female">
                <label for="102">
                <input type="radio" value="female" name="class" id="102" >
                Female
                </label>

                </span>
                <span class="others">
                    <label for="103">
                <input type="radio" value="others" name="class" id="103">
                Others
                </label>
                
                </span>
                <br>
                <span class="age">
                    <label>Age :</label>
                    <br>
                    <input type="number" min="18" max="60" placeholder="Enter your age" class="age1">
                </span>
                <span class="blood-group">
                    <label>Blood Group :</label>
                    <!-- <input type="text"  placeholder="Enter blood group" value="" class="blood-group1"> -->
                   <br><br> <select>
                        <option></option>
                        <option>A+</option>
                        <option>B+</option>
                        <option>AB+</option>
                        <option>AB</option>
                        <option>O+</option>
                        <option>O-</option>
                    </select>
                   
                </span>
                <br>
                <label>Address :</label>
                <br>
                <input type="text" placeholder="Enter your address" class="address">
                <br>
                <label>Prefered Date :</label>
                <br>
                <input type="date" name="date" placeholder="dd-mm-yy" class="date">
                <br>
                <button type="submit" class="submit">Register</button>
            </form>
        </div>
        <div class="image2">
           <img src="Blood.png" height="170px">
            
            <!-- <img src="https://images.app.goo.gl/Ad1DXk5Jh8BPpEnr9" height="200px" width="200px"> -->
        </div>
    
    
</body>
</html>
