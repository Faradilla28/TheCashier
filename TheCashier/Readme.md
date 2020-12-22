# TheCashier
Aplikasi ini mencakup fungsi perhitungan barang yang dipilih oleh pelanggan.

## Scope & Functionalities
- user dapat memasukan item yang dipilih
- user dapat memilih type dari belanjaan yang dipilih
- user dapat memasukan jumlah
- user dapat menekan tombol "Tambahkan".

## How Does it works?
Diawali dari method `MainWindow` pada class MainWindow.xaml.cs, dapat dideklarasikan sebagai berikut :
```csharp
public MainWindow()
        {
            InitializeComponent();
            calculator = new Calculator();
            listBox.ItemsSource = calculator.getListItem();

        }
```