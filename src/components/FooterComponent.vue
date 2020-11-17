<template>
    <footer class="bg-dark text-white" id="main-footer">
        <div class="container">
            <div class="row">
                <div class="col text-center py-4">
                    <h3>LopLAB</h3>
                    <p>Copyright &copy;{{new Date().getFullYear()}}</p>
                    <button class="btn btn-primary" data-toggle="modal" data-target="#contactModal">contact us</button>
                </div>
            </div>
        </div>

        <!-- contact modal -->
        <div class="modal fade text-dark" id="contactModal">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Contact us</h5>
                        <button class="close" data-dismiss="modal"><span>&times;</span></button>
                    </div>
                    <div class="modal-body">
                        <form action="">
                            <div class="form-group">
                                <label for="name">Name</label>
                                <input type="text" class="form-control">
                            </div>
                            <div class="form-group">
                                <label for="email">Email</label>
                                <input type="text" class="form-control">
                            </div>
                            <div class="form-group">
                                <label for="name">Message</label>
                                <textarea name="message" class="form-control" rows="5"></textarea>
                            </div>
                        </form>
                    </div>
                    <div class="modal-footer">
                        <button class="btn btn-primary btn-block">Submit</button>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>