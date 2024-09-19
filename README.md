# Customizable_Button_Maker
# I have created a customizable button using HTML, CSS, and JavaScript that accepts inputs for background color, font color, font size, font weight, padding, and border radius, and generates a customized button
# HTML CODE
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="button-maker-bg-container p-4">
        <h1 class="button-maker-heading text-center mb-4">Button Maker</h1>
        <div class="button-maker-container bg-light pt-4 pb-4">
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-7">
                        <p class="input-label">BACKGROUND COLOR</p>
                        <input class="user-input" type="text" id="bgColorInput" />
                        <p class="input-label">FONT COLOR</p>
                        <input class="user-input" type="text" id="fontColorInput" />
                        <p class="input-label">FONT SIZE (in px)</p>
                        <input class="user-input" type="text" id="fontSizeInput" />
                        <p class="input-label">FONT WEIGHT</p>
                        <input class="user-input" type="text" id="fontWeightInput" />
                        <p class="input-label">PADDING (in px)</p>
                        <input class="user-input" type="text" id="paddingInput" />
                        <p class="input-label">BORDER RADIUS (in px)</p>
                        <input class="user-input" type="text" id="borderRadiusInput" />
                        <div class="text-right mt-4">
                            <button id="applyButton" class="btn btn-primary" onclick="applyButtonClick()">
                                Apply
                            </button>
                        </div>
                    </div>
                    <div class="col-12 col-md-5 mt-4 text-center">
                        <button class="custom-button" id="customButton">Custom Button</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
