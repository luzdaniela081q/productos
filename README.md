-- phpMyAdmin SQL Dump
-- version 5.2.1
-- https://www.phpmyadmin.net/
--
-- Servidor: 127.0.0.1
-- Tiempo de generación: 12-11-2025 a las 06:36:57
-- Versión del servidor: 10.4.32-MariaDB
-- Versión de PHP: 8.2.12

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Base de datos: `tienda_de_peluches`
--

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `productos`
--

CREATE TABLE `productos` (
  `ID` int(11) NOT NULL,
  `Nombre` varchar(50) DEFAULT NULL,
  `Descripcion` varchar(255) NOT NULL,
  `precio` decimal(10,2) DEFAULT NULL,
  `stock` int(10) UNSIGNED NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=ascii COLLATE=ascii_general_ci;

--
-- Volcado de datos para la tabla `productos`
--

INSERT INTO `productos` (`ID`, `Nombre`, `Descripcion`, `precio`, `stock`) VALUES
(2, NULL, '', NULL, 0),
(15289, 'Oso Teddy', 'Oso de peluche cl?sico', 250.99, 50),
(28765, 'Vaca Lechera', 'Vaquita lechera grande', 450.00, 89),
(30009, 'Gato mimoso', 'Gatito de peluche, super suave y rellenito,\r\ntama?o 30cm', 350.00, 10),
(39220, 'Le?n Melenudo', 'Le?n de peluche con melena abundante', 340.00, 29),
(39391, 'Perro fiel', 'Perro de peluche que parece tu mejor compa??a y amistad m?s leal, tama?o 1m', 400.00, 12),
(45987, 'Pato amarillo', 'Pato de peluche afelpado ', 199.00, 1),
(65428, 'Koala Dormilon', 'Siempre tendr? sue?o', 550.00, 76),
(91872, 'Conejo Peludito', 'Conejo bonito, de afelpado rosita, suave', 290.05, 30),
(213456, 'Mono Saltar?n', 'La mejor compra que te puedes llevar', 255.00, 19),
(665748, 'Rana Coqu?', 'rana de canta por la noche, con un solo click', 900.00, 26),
(999992, 'Oveja Lanuda', 'Color: blanco marfil o crema, con algunos detalles beige o gris claro para dar dimensi?n al ?vell?n?.\r\n\r\n', 500.00, 70),
(1234567, 'Tigre Rayado', 'Un tigre bonito', 200.00, 4),
(8292929, 'Elefante Trompitas', 'Si te encantan los elefantes, no dudes en comprar este peluchito', 220.00, 44),
(84844848, 'Zorro Astuto', 'Peluche con ojos desafiantes', 230.00, 98),
(98760123, 'Serpiente Enroscada', 'Es larga y enroscada, 30cm', 600.00, 61),
(99928281, 'Hipop?tamo Rosa', 'peluchito rosado y peludito', 1000.00, 91),
(111111118, 'Drag?n Escamoso', 'Sus escamas son brillantes, 2m', 1500.00, 100),
(183682629, 'Canguro Boxeador', 'Cuidado con nuestro canguro preparado para boxear', 870.00, 67),
(757575775, 'Oso Panda', 'Peluche adorable', 340.00, 37),
(767685841, 'Ping?ino Friolento', 'Peluche de ping?ino que le encanta el fr?o ', 390.00, 11);

--
-- Índices para tablas volcadas
--

--
-- Indices de la tabla `productos`
--
ALTER TABLE `productos`
  ADD PRIMARY KEY (`ID`);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
