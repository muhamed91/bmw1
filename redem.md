@include mobile($mobile) {
    .second_nav {
        display: none;
    }
    
    
    .mobile-subnav {
        position: relative;
        height: 54px;
        padding: 5px 0;
        text-align: center;
    
    
        .lenkrad {
            padding-right: 0;
            font-size: 30px;
        }
    
        .probe_btn {
            position: absolute;
            right: 0;
            width: 65px;
        }
        p {
            display: inline;
            font-weight: bold;
            font-size: 18px;
            line-height: 2.5;
        }
    }
    
    .i-down {
        position: absolute;
        right: 75px;
        top: 18px;
    }
}


@include md($tablet) {
    .second_nav {
        display: none;
    }
    
    
    .mobile-subnav {
        position: relative;
        height: 54px;
        padding: 5px 0;
        text-align: center;
    
    
        .lenkrad {
            padding-right: 0;
            font-size: 30px;
        }
    
        .probe_btn {
            position: absolute;
            right: 0;
            width: 65px;
            top: -23px;
        }
        p {
            display: inline;
            font-weight: bold;
            font-size: 18px;
            line-height: 2.5;
        }
    }
    
    .i-down {
        position: absolute;
        right: 75px;
        top: 18px;
    }
}
