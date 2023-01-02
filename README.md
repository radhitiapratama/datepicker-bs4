
## Penggunaan

Struktur di head

```html
    <head>
      <!-- Bootstrap 4  -->
      <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
        integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N"
        crossorigin="anonymous"
      />

      <!-- Tempus Dominus Bootstrap 4 -->
      <link
        rel="stylesheet"
        href="/path/to/tempusdominus-bootstrap-4.min.css"
      />
    </head>

```


Struktur di body

```html
<!-- Jquery -->
    <script
      src="https://code.jquery.com/jquery-3.6.3.js"
      integrity="sha256-nQLuAZGRRcILA+6dMBOvcRh5Pe310sBpanc6+QBmyVM="
      crossorigin="anonymous"
    ></script>

    <!-- Font Awesome -->
    <!-- Your Kit -->
    <script src="https://kit.fontawesome.com/YOURKIT"crossorigin="anonymous"></script>

    <!-- Bootstrap 4 -->
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
      integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
      crossorigin="anonymous"
    ></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.min.js"integrity="sha384-+sLIOodYLS7CIrQpBjl+C7nPvqq+FbNUBDunl/OZv93DB7Ln/533i8e/mZXLi/P+"
      crossorigin="anonymous"
    ></script>

    <!-- Moment and id JS -->
    <script type="text/javascript" src="/path/to/moment.js"></script>
    <script type="text/javascript" src="/path/to/id.js"></script>

    <!-- Tempus Dominus Bootstrap 4 -->
    <script type="text/javascript" src="/path/to/tempusdominus-bootstrap-4.min.js"></script>
```

html tag

```html
<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div class="form-group">
                <div class="input-group date" id="datetimepicker1" data-target-input="nearest">
                    <input type="text" class="form-control datetimepicker-input" data-target="#datetimepicker1"/>
                    <div class="input-group-append" data-target="#datetimepicker1" data-toggle="datetimepicker">
                        <div class="input-group-text"><i class="fa fa-calendar"></i></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

```

Tambahkan script berikut di file js pribadi anda

```javascript
  $('#datetimepicker1').datetimepicker({
    locale: 'id',
  });
```
