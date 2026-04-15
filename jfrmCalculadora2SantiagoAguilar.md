/\*

&#x20;\* Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license

&#x20;\* Click nbfs://nbhost/SystemFileSystem/Templates/GUIForms/JFrame.java to edit this template

&#x20;\*/



/\*\*

&#x20;\*

&#x20;\* @author santi

&#x20;\*/

public class Calculadora extends javax.swing.JFrame {

&#x20;   

&#x20;   private static final java.util.logging.Logger logger = java.util.logging.Logger.getLogger(Calculadora.class.getName());

&#x20;   private String entrada="";

&#x20;   private int numero1, numero2;

&#x20;   private String operador;

&#x20;   public Calculadora() {

&#x20;       initComponents();

&#x20;       this.setLocationRelativeTo(null);

&#x20;       this.setTitle("Calculadora Santiago Turcios");

&#x20;   }





&#x20;   @SuppressWarnings("unchecked")

&#x20;   // <editor-fold defaultstate="collapsed" desc="Generated Code">//GEN-BEGIN:initComponents

&#x20;   private void initComponents() {



&#x20;       jbtn4 = new javax.swing.JButton();

&#x20;       jbtn5 = new javax.swing.JButton();

&#x20;       jbtn6 = new javax.swing.JButton();

&#x20;       jbtnMulti = new javax.swing.JButton();

&#x20;       jbtnBorrarTodo = new javax.swing.JButton();

&#x20;       jbtn1 = new javax.swing.JButton();

&#x20;       jbtn2 = new javax.swing.JButton();

&#x20;       jbtn3 = new javax.swing.JButton();

&#x20;       jbtnResta = new javax.swing.JButton();

&#x20;       jbtnRaiz = new javax.swing.JButton();

&#x20;       jbtn0 = new javax.swing.JButton();

&#x20;       jbtnIgual = new javax.swing.JButton();

&#x20;       jbtnMas = new javax.swing.JButton();

&#x20;       jbtnBorrar = new javax.swing.JButton();

&#x20;       jbtn7 = new javax.swing.JButton();

&#x20;       jbtn8 = new javax.swing.JButton();

&#x20;       jbtn9 = new javax.swing.JButton();

&#x20;       jbtnDivi = new javax.swing.JButton();

&#x20;       jbtnPorcentaje = new javax.swing.JButton();

&#x20;       jbxtCantidad = new javax.swing.JTextField();



&#x20;       setDefaultCloseOperation(javax.swing.WindowConstants.EXIT\_ON\_CLOSE);



&#x20;       jbtn4.setText("4");

&#x20;       jbtn4.addActionListener(this::jbtn4ActionPerformed);



&#x20;       jbtn5.setText("5");

&#x20;       jbtn5.addActionListener(this::jbtn5ActionPerformed);



&#x20;       jbtn6.setText("6");

&#x20;       jbtn6.addActionListener(this::jbtn6ActionPerformed);



&#x20;       jbtnMulti.setText("\*");

&#x20;       jbtnMulti.addActionListener(this::jbtnMultiActionPerformed);



&#x20;       jbtnBorrarTodo.setText("AC");

&#x20;       jbtnBorrarTodo.addActionListener(this::jbtnBorrarTodoActionPerformed);



&#x20;       jbtn1.setText("1");

&#x20;       jbtn1.addActionListener(this::jbtn1ActionPerformed);



&#x20;       jbtn2.setText("2");

&#x20;       jbtn2.addActionListener(this::jbtn2ActionPerformed);



&#x20;       jbtn3.setText("3");

&#x20;       jbtn3.addActionListener(this::jbtn3ActionPerformed);



&#x20;       jbtnResta.setText("-");

&#x20;       jbtnResta.addActionListener(this::jbtnRestaActionPerformed);



&#x20;       jbtnRaiz.setText("RC");

&#x20;       jbtnRaiz.addActionListener(this::jbtnRaizActionPerformed);



&#x20;       jbtn0.setText("0");

&#x20;       jbtn0.addActionListener(this::jbtn0ActionPerformed);



&#x20;       jbtnIgual.setText("=");

&#x20;       jbtnIgual.addActionListener(this::jbtnIgualActionPerformed);



&#x20;       jbtnMas.setFont(new java.awt.Font("Segoe UI", 0, 10)); // NOI18N

&#x20;       jbtnMas.setText("+");

&#x20;       jbtnMas.addActionListener(this::jbtnMasActionPerformed);



&#x20;       jbtnBorrar.setText("C");

&#x20;       jbtnBorrar.addActionListener(this::jbtnBorrarActionPerformed);



&#x20;       jbtn7.setText("7");

&#x20;       jbtn7.addActionListener(this::jbtn7ActionPerformed);



&#x20;       jbtn8.setText("8");

&#x20;       jbtn8.addActionListener(this::jbtn8ActionPerformed);



&#x20;       jbtn9.setText("9");

&#x20;       jbtn9.addActionListener(this::jbtn9ActionPerformed);



&#x20;       jbtnDivi.setText("/");

&#x20;       jbtnDivi.addActionListener(this::jbtnDiviActionPerformed);



&#x20;       jbtnPorcentaje.setText("%");

&#x20;       jbtnPorcentaje.addActionListener(this::jbtnPorcentajeActionPerformed);



&#x20;       jbxtCantidad.setFont(new java.awt.Font("Segoe UI", 0, 18)); // NOI18N

&#x20;       jbxtCantidad.setText("0.0");

&#x20;       jbxtCantidad.setEnabled(false);



&#x20;       javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());

&#x20;       getContentPane().setLayout(layout);

&#x20;       layout.setHorizontalGroup(

&#x20;           layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)

&#x20;           .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()

&#x20;               .addContainerGap(49, Short.MAX\_VALUE)

&#x20;               .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)

&#x20;                   .addComponent(jbxtCantidad, javax.swing.GroupLayout.Alignment.TRAILING)

&#x20;                   .addGroup(layout.createSequentialGroup()

&#x20;                       .addComponent(jbtn7, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtn8, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtn9, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnDivi, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnPorcentaje, javax.swing.GroupLayout.PREFERRED\_SIZE, 50, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;                   .addGroup(layout.createSequentialGroup()

&#x20;                       .addComponent(jbtn4, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtn5, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtn6, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnMulti, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT\_SIZE, Short.MAX\_VALUE)

&#x20;                       .addComponent(jbtnBorrarTodo, javax.swing.GroupLayout.PREFERRED\_SIZE, 50, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;                   .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()

&#x20;                       .addComponent(jbtn1, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtn2, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtn3, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnResta, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnRaiz, javax.swing.GroupLayout.PREFERRED\_SIZE, 50, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;                   .addGroup(layout.createSequentialGroup()

&#x20;                       .addComponent(jbtn0, javax.swing.GroupLayout.PREFERRED\_SIZE, 34, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnBorrar, javax.swing.GroupLayout.PREFERRED\_SIZE, 49, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnMas, javax.swing.GroupLayout.PREFERRED\_SIZE, 43, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                       .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;                       .addComponent(jbtnIgual, javax.swing.GroupLayout.DEFAULT\_SIZE, javax.swing.GroupLayout.DEFAULT\_SIZE, Short.MAX\_VALUE)))

&#x20;               .addGap(45, 45, 45))

&#x20;       );

&#x20;       layout.setVerticalGroup(

&#x20;           layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)

&#x20;           .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()

&#x20;               .addGap(43, 43, 43)

&#x20;               .addComponent(jbxtCantidad, javax.swing.GroupLayout.PREFERRED\_SIZE, 66, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;               .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, 32, Short.MAX\_VALUE)

&#x20;               .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)

&#x20;                   .addComponent(jbtn7, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtn8, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtn9, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnDivi, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnPorcentaje, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;               .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;               .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)

&#x20;                   .addComponent(jbtn4, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtn5, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtn6, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnMulti, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnBorrarTodo, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;               .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;               .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)

&#x20;                   .addComponent(jbtn1, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtn2, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtn3, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnResta, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnRaiz, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;               .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)

&#x20;               .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)

&#x20;                   .addComponent(jbtn0, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnIgual, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnMas, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE)

&#x20;                   .addComponent(jbtnBorrar, javax.swing.GroupLayout.PREFERRED\_SIZE, 37, javax.swing.GroupLayout.PREFERRED\_SIZE))

&#x20;               .addGap(45, 45, 45))

&#x20;       );



&#x20;       pack();

&#x20;   }// </editor-fold>//GEN-END:initComponents



&#x20;   private void jbtn0ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn0ActionPerformed

&#x20;       entrada= entrada + 0;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn0ActionPerformed



&#x20;   private void jbtn1ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn1ActionPerformed

&#x20;       entrada= entrada + 1;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn1ActionPerformed



&#x20;   private void jbtn2ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn2ActionPerformed

&#x20;       entrada= entrada + 2;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn2ActionPerformed



&#x20;   private void jbtn3ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn3ActionPerformed

&#x20;       entrada= entrada + 3;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn3ActionPerformed



&#x20;   private void jbtn4ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn4ActionPerformed

&#x20;       entrada= entrada + 4;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn4ActionPerformed



&#x20;   private void jbtn5ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn5ActionPerformed

&#x20;       entrada= entrada + 5;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn5ActionPerformed



&#x20;   private void jbtn6ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn6ActionPerformed

&#x20;       entrada= entrada + 6;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn6ActionPerformed



&#x20;   private void jbtn7ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn7ActionPerformed

&#x20;       entrada= entrada + 7;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn7ActionPerformed



&#x20;   private void jbtn8ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn8ActionPerformed

&#x20;       entrada= entrada + 8;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn8ActionPerformed



&#x20;   private void jbtn9ActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtn9ActionPerformed

&#x20;       entrada= entrada + 9;

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtn9ActionPerformed



&#x20;   private void jbtnDiviActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnDiviActionPerformed

&#x20;       numero1=Integer.parseInt(entrada);

&#x20;       entrada="";

&#x20;       operador="/";

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtnDiviActionPerformed



&#x20;   private void jbtnMultiActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnMultiActionPerformed

&#x20;       numero1=Integer.parseInt(entrada);

&#x20;       entrada="";

&#x20;       operador="\*";

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtnMultiActionPerformed



&#x20;   private void jbtnRestaActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnRestaActionPerformed

&#x20;       numero1=Integer.parseInt(entrada);

&#x20;       entrada="";

&#x20;       operador="-";

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtnRestaActionPerformed



&#x20;   private void jbtnMasActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnMasActionPerformed

&#x20;       numero1=Integer.parseInt(entrada);

&#x20;       entrada="";

&#x20;       operador="+";

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtnMasActionPerformed



&#x20;   private void jbtnIgualActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnIgualActionPerformed

&#x20;       double resultado;

&#x20;       numero2=Integer.parseInt(entrada);

&#x20;       jbxtCantidad.setText("");

&#x20;       entrada="";

&#x20;       if(operador.equals("\*")){

&#x20;           resultado=numero1\*numero2;

&#x20;           entrada=String.valueOf(resultado);

&#x20;           jbxtCantidad.setText(entrada);

&#x20;       }else if(operador.equals("-")){

&#x20;           resultado=numero1-numero2;

&#x20;           entrada=String.valueOf(resultado);

&#x20;           jbxtCantidad.setText(entrada);

&#x20;       }else if(operador.equals("+")){

&#x20;           resultado=numero1+numero2;

&#x20;           entrada=String.valueOf(resultado);

&#x20;           jbxtCantidad.setText(entrada);

&#x20;       }else if(operador.equals("/")){

&#x20;           resultado=numero1/numero2;

&#x20;           entrada=String.valueOf(resultado);

&#x20;           jbxtCantidad.setText(entrada);

&#x20;       }

&#x20;   }//GEN-LAST:event\_jbtnIgualActionPerformed



&#x20;   private void jbtnBorrarActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnBorrarActionPerformed

&#x20;   String texto = jbxtCantidad.getText();

&#x20;   

&#x20;   if (texto.length() > 1){

&#x20;       texto = texto.substring(0, texto.length() - 1);

&#x20;       jbxtCantidad.setText(texto);

&#x20;   } else {

&#x20;       jbxtCantidad.setText("0");

&#x20;   }

&#x20;   }//GEN-LAST:event\_jbtnBorrarActionPerformed



&#x20;   private void jbtnRaizActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnRaizActionPerformed

&#x20;       double valor = Double.parseDouble(jbxtCantidad.getText());

&#x20;       

&#x20;       if (valor >= 0) {

&#x20;           valor = Math.sqrt(valor);

&#x20;           jbxtCantidad.setText(String.valueOf(valor));

&#x20;       } else {

&#x20;           jbxtCantidad.setText("Error");

&#x20;       }

&#x20;   }//GEN-LAST:event\_jbtnRaizActionPerformed



&#x20;   private void jbtnBorrarTodoActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnBorrarTodoActionPerformed

&#x20;       entrada="0";

&#x20;       jbxtCantidad.setText(entrada);

&#x20;   }//GEN-LAST:event\_jbtnBorrarTodoActionPerformed



&#x20;   private void jbtnPorcentajeActionPerformed(java.awt.event.ActionEvent evt) {//GEN-FIRST:event\_jbtnPorcentajeActionPerformed

&#x20;       try {

&#x20;       double valor = Double.parseDouble(jbxtCantidad.getText());

&#x20;       

&#x20;       valor = valor / 100;

&#x20;       

&#x20;       jbxtCantidad.setText(String.valueOf(valor));

&#x20;       } catch (NumberFormatException e) {

&#x20;           jbxtCantidad.setText("Error");

&#x20;       }

&#x20;   }//GEN-LAST:event\_jbtnPorcentajeActionPerformed



&#x20;   /\*\*

&#x20;    \* @param args the command line arguments

&#x20;    \*/

&#x20;   public static void main(String args\[]) {

&#x20;       /\* Set the Nimbus look and feel \*/

&#x20;       //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">

&#x20;       /\* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.

&#x20;        \* For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 

&#x20;        \*/

&#x20;       try {

&#x20;           for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {

&#x20;               if ("Nimbus".equals(info.getName())) {

&#x20;                   javax.swing.UIManager.setLookAndFeel(info.getClassName());

&#x20;                   break;

&#x20;               }

&#x20;           }

&#x20;       } catch (ReflectiveOperationException | javax.swing.UnsupportedLookAndFeelException ex) {

&#x20;           logger.log(java.util.logging.Level.SEVERE, null, ex);

&#x20;       }

&#x20;       //</editor-fold>



&#x20;       /\* Create and display the form \*/

&#x20;       java.awt.EventQueue.invokeLater(() -> new Calculadora().setVisible(true));

&#x20;   }



&#x20;   // Variables declaration - do not modify//GEN-BEGIN:variables

&#x20;   private javax.swing.JButton jbtn0;

&#x20;   private javax.swing.JButton jbtn1;

&#x20;   private javax.swing.JButton jbtn2;

&#x20;   private javax.swing.JButton jbtn3;

&#x20;   private javax.swing.JButton jbtn4;

&#x20;   private javax.swing.JButton jbtn5;

&#x20;   private javax.swing.JButton jbtn6;

&#x20;   private javax.swing.JButton jbtn7;

&#x20;   private javax.swing.JButton jbtn8;

&#x20;   private javax.swing.JButton jbtn9;

&#x20;   private javax.swing.JButton jbtnBorrar;

&#x20;   private javax.swing.JButton jbtnBorrarTodo;

&#x20;   private javax.swing.JButton jbtnDivi;

&#x20;   private javax.swing.JButton jbtnIgual;

&#x20;   private javax.swing.JButton jbtnMas;

&#x20;   private javax.swing.JButton jbtnMulti;

&#x20;   private javax.swing.JButton jbtnPorcentaje;

&#x20;   private javax.swing.JButton jbtnRaiz;

&#x20;   private javax.swing.JButton jbtnResta;

&#x20;   private javax.swing.JTextField jbxtCantidad;

&#x20;   // End of variables declaration//GEN-END:variables

}



