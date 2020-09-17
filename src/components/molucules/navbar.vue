<template>
    <div class="container">
            <nav class="navbar navbar-expand-lg navbar-light bg-white">
                <h2 class="navbar-brand mt-2 color-text">Chatting kuyy..</h2>
                <span class="navbar-toggler-icon ml-auto"></span>
            </nav>
            <div class="container row ml-1">
                <input class="form-control pt-4 pb-4 mb-3 mr-sm-2 col-10 rounded-search" type="search" placeholder="Type your message..." aria-label="Search">
                <h2 class="col-1 mb-3 color">+</h2>
                <div class="list-group col-12 list-group-horizontal" id="list-tab" role="tablist">
                    <a class="list-group-item list-group-item-action border-0" data-toggle="list" href="#" role="tab" aria-controls="home">All</a>
                    <a class="list-group-item list-group-item-action rounded-pill border-0 active" data-toggle="list" href="#" role="tab" aria-controls="profile">Important</a>
                    <a class="list-group-item list-group-item-action border-0" data-toggle="list" href="#" role="tab" aria-controls="messages">Unread</a>
                </div>
            </div>
        </div>
</template>

<style scoped>
.rounded-search {
    border-radius: 15px;
}
</style>
