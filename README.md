Cookie 的名字：loginInfo
Session for loginInfo: userInfo
Example: 
    session_start();
    echo "Username: ". $_SESSION["userInfo"]["username"]. "<br>";
    echo "Email: ". $_SESSION["userInfo"]["email"] . "<br>";
    echo "Picture Path: ". $_SESSION["userInfo"]["picturePath"] . "<br>";
    echo "Picture Name: ". $_SESSION["userInfo"]["pictureName"] . "<br>";
