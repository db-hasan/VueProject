
<template>
    <div class="">
        <div class="text-end">
            <RouterLink to="" class="btn btn-sm btn-dark"><i class="fas fa-plus-circle"></i> Add Data</RouterLink>
        </div>
        <hr>
        <div class="custom-scrollbar-table">
            <table id="myTable" class="table">
                <thead>
                    <tr>
                        <th><span class="">ID</span></th>
                        <th><span class="pe-5">Name</span></th>
                        <th><span class="">Status</span></th>
                        <th class="ps-5">Action</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1111222</td>
                        <td>Proxy Tanvir</td>
                        <td>Active</td>
                        <td class="icons">
                            <RouterLink to="" type="button" class="btn view"><i class="fa-solid fa-eye"></i></RouterLink>
                            <RouterLink to="" type="button" class="btn edit"><i class="fa-solid fa-pen"></i></RouterLink>
                            <RouterLink to="" type="button" class="btn delete"
                                onclick="return confirm('Are you sure dalete')"><i class="fa-solid fa-trash"></i>
                            </RouterLink>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

