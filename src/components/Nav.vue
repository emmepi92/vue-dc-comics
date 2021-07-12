<template>
    <div class="nav-container container">
        <div class="nav-logo">
            <img src="../assets/dc-logo.png" alt="">
        </div>

        <div class="nav-menu">
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </div>
    
    </div>
    
</template>

<script>
export default {
    name:"Nav"    
}
</script>


<style lang="scss" scoped>
    .nav-container {
        display: flex;
        justify-content: space-between;
        align-items: center;

        .nav-logo {
            img {
                width: 100px;
            }

        }

        .nav-menu {
            ul {
                display: flex;
                li {
                    margin: 0 18px;
                    text-transform: uppercase;
                    border-bottom: 4px solid white;
                    height: 120px;
                    line-height: 120px;
                    font-weight: 500;

                    &:hover {
                        border-bottom: 4px solid #18f;
                    }
                }
            } 

        }
    }


</style>