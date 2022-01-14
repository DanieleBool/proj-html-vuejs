<template>
    <div class="container">
        <div class="logo">
            <img src="../../assets/img/logo-restaurant.png" alt="logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Culinary History</a></li>
                <li><a href="#">Our Team</a></li>
                <li><a href="#">Our Menu</a></li>
                <li><a href="#">Takeout <span class="new">New</span></a></li>
                <li><a href="#">Bulletin</a></li>
                <li><a href="#">Reservations</a></li>
                <li><a href="#"><i class="fas fa-shopping-cart"></i><font-awesome-icon icon="shopping-chart" /></a></li>
            </ul>
        </nav>

        <!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Navbar</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#">Pricing</a>
                    </li>
                    <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Dropdown link
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                        <li><a class="dropdown-item" href="#">Action</a></li>
                        <li><a class="dropdown-item" href="#">Another action</a></li>
                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                    </li>
                </ul>
                </div>
            </div>
        </nav> -->
    </div>
</template>

<script>
export default {
    name:'navBar',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';

    .container {
        align-self: flex-start;
        height: 100px; 
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: absolute;
        left: 0;
        right: 0;
        // backdrop-filter: brightness(70%);
        .logo {
            width: 10%;

            .logo img{
                height: 70px;
            }
        }

        nav {
            
            ul {
                display: flex;
                list-style: none;
                li {
                    padding: 0px 15px;
                    a {
                        font-family: -apple-system, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                        font-weight: bolder;
                        display: inline-block;
                        text-decoration: none;
                        color: $wGray;
                        line-height: 85px;
                        font-weight: 500;
                        .new{
                            color: white;
                            font-size: 11px;
                            border: solid $wGray 1px;
                            padding: 2px 6px 4px;
                            // line-height: px;
                            margin-left: 3px;
                        }
                    };
                    .active, :hover {
                        color: white;
                    };                    
                };
                
            };
        };

    }


</style>