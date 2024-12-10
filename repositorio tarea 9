import javax.swing.*;
import java.awt.*;
import java.awt.event.*;
import javax.swing.table.DefaultTableModel;

public class FarmaciaApp extends JFrame {

    //  formulario de productos
    private final JTextField txtCodigo;
    private JTextField txtNombre, txtPrecio, txtCantidad;
    private JTable tablaProductos;
    private JButton btnAgregar, btnEliminar, btnBuscar;

// Componentes del formulario de ventas
    private JComboBox<String> comboProductos;
    private JTextField txtCantidadVenta;
    private JButton btnVender;
    private JTextArea txtAreaVentas;

    // Modelo de tabla para los productos
    private DefaultTableModel modeloProductos;

    public FarmaciaApp() {
        // Crear la ventana principal
        setTitle("Gestión de Farmacia");
        setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        setSize(800, 600);
        setLocationRelativeTo(null);
   // Crear los paneles para organizar los componentes
        JPanel panelProductos = new JPanel(new GridLayout(5, 2));
        JPanel panelVentas = new JPanel(new GridLayout(3, 2));

        // Agregar componentes al panel de productos
        panelProductos.add(new JLabel("Código:"));
        panelProductos.add(txtCodigo = new JTextField());
        // ... (Agregar los demás componentes del panel de productos)
// Agregar componentes al panel de ventas
        panelVentas.add(new JLabel("Producto:"));
        panelVentas.add(comboProductos = new JComboBox<>());
        // ... (Agregar los demás componentes del panel de ventas)

        // Crear un panel principal para agregar los paneles de productos y ventas
        JPanel panelPrincipal = new JPanel(new GridLayout(1, 2));
        panelPrincipal.add(panelProductos);
        panelPrincipal.add(panelVentas);
 // Agregar el panel principal a la ventana
        add(panelPrincipal, BorderLayout.CENTER);

        // Crear la barra de menú
        JMenuBar menuBar = new JMenuBar();
        JMenu menuArchivo = new JMenu("Archivo");
        JMenuItem menuItemSalir = new JMenuItem("Salir");
        menuItemSalir.addActionListener((ActionEvent e) -> {
            System.exit(0);
        });
menuArchivo.add(menuItemSalir);
        menuBar.add(menuArchivo);
        setJMenuBar(menuBar);

        // Mostrar la ventana
        setVisible(true);
    }

    // Los métodos agregarProducto(), eliminarProducto(), venderProducto() y actualizarComboBoxProductos()
    // ya están definidos en la respuesta anterior

public static void main(String[] args) {
        FarmaciaApp farmaciaApp = new FarmaciaApp();
}
}
