<template lang='pug'>
header.container
    .header.row.justify-content-center.align-items-center.position-relative
        .col-12.col-md-3.text-center.text-md-start
            a( href='#' )
                    img.logo( src='@/assets/images/logo.png' alt='logo')
        nav.col.px-0
            ul
                li.d-flex.align-items-end.me-3
                    a.me-1.d-sm-none.d-block( href='#' )
                        img( src='@/assets/images/title_triangle.png' alt='taiwan_attraction')
                    a.text-pink( href='#' ) 台灣景點
                li.d-flex.align-items-end.me-3
                    a.me-1.d-sm-none.d-block( href='#' )
                        img( src='@/assets/images/title_square.png' alt='Gourmet_accommodation')
                    a.text-yellow( href='#' ) 美食住宿
                li.d-flex.align-items-end
                    a.me-1.d-sm-none.d-block( href='#' )
                        img( src='@/assets/images/title_circle.png' alt='Attractions_Transportation')
                    a.text-green( href='#' ) 景點交通
        .shadow.shadow-left.d-sm-none.d-md-block.d-none
        .shadow.shadow-right.d-sm-none.d-md-block.d-none
    .search-area.position-relative.d-flex.justify-content-center.align-items-center
        .search-content.d-flex.flex-column
            h1.text-white.h1.d-md-none.d-block Welc#[span.titleCircle]me t#[span.titleSquare]#[span.text-pink Taiwan]
            p.text-white.h4.d-md-none.d-block 台北、台中、台南、屏東、宜蘭……遊遍台灣
            .d-flex.mt-1.d-sm-none
                input.col.search.me-1( placeholder='搜尋關鍵字' )            
                button.btn.bg-yellow.h-5.w-5
                    img( src='@/assets/images/location.png' alt='location button')
            .d-flex.mt-1.position-relative
                select.col.select.me-1( name='category' )
                    option( value='' ) 選擇類別
                select.col.select.me-1( name='city' )
                    option( value='' ) 不分縣市
                button.btn.btn-pink.bg-pink.h-5.w-5
                    img.d-flex.align-items-center.justify-content-center( src='@/assets/images/search.png' alt='search button' )
        .shadow.shadow-left.d-md-none.d-sm-block.d-block
        .shadow.shadow-right.d-md-none.d-sm-block.d-block

</template>