# API_Med-Centro-m-dico-Zenith
![Byte Blast]()
<p>En este repositorio trabajere un proyecto de parte de la Byte Blast Tech para el centro medico privado Zenith con el objetivo de optimizar sus bases de datos de su centro medico que cuenta con medico pacientes y un expediente de citas </p>

## Objetivos de la API:
- Implementar un sistema de carga para datos de los doctores del centro medico 
- Implementar un sistema para el registro de los pacientes del centro medico 
- realizar un sistema que pueda almacenar las especificaciones de una cita para un paciente
- Todos los sistemas deben tener funciones de Crear Actualizar , Registrar y eleminar (CRUD) de parte del administrativo del centro medico.

## Requisitos de Cada sistema

| Nombre del sistema              | Rquisitos                   | Funciones |
|------------------------------|-------------------------|---------|
|Sistema gestor para Pacientes   | Campos Requeridos: _id, nombre, apellido,fechaNacimiento, género, dirección, teléfono, email, númeroHistoriaClinica, seguroMedico, fechaRegistro| CRUD   |
| Sistema gestor para Doctores| Campos Requeridos: _id, nombre, apellido, especialidad, teléfono, email, horarioAtención, consultorio ,fechaRegistro  |CRUD     |
| Sistema gestor para Citas      | Campos Requeridos: _id,pacienteId, doctorId, fechaCita, motivo,estado, notas, fechaCreación, fechaActualización    | CRUD    |


 