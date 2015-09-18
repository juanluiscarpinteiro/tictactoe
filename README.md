# tictactoe
tictactoe game
package Game;

import java.awt.*;
import java.awt.event.*;
import javax.swing.*;
import javax.swing.GroupLayout;
import javax.swing.LayoutStyle;

 
 
 
/** 
 * @author frame coding Bradley Chelsey, juan carpinteiro. 
 */

public class tictactoe extends JFrame {
		Main main= new Main();
		
	
        public tictactoe() {
                initComponents();
        }
 
        public void button1ActionPerformed(ActionEvent e) {
               if(button1.getText().equals(""))
               {
            	   if(Main.playerTurn==true)
            	   {
            		   button1.setText("X");
            		   Main.checkforwin();
            		   Main.playerTurn=false;
             	   }else
             	   {
             		   button1.setText("O");
             		   Main.checkforwin();
             		   Main.playerTurn=true;
             	   }
               }
        }
 
        public void button2ActionPerformed(ActionEvent e) {
        	  if(button2.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button2.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button2.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button3ActionPerformed(ActionEvent e) {
        	  if(button3.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button3.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button3.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button4ActionPerformed(ActionEvent e) {
        	  if(button4.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button4.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button4.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button5ActionPerformed(ActionEvent e) {
        	  if(button5.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button5.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button5.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button6ActionPerformed(ActionEvent e) {
        	  if(button6.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button6.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button6.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button7ActionPerformed(ActionEvent e) {
        	  if(button7.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button7.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button7.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button8ActionPerformed(ActionEvent e) {
        	  if(button8.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button8.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button8.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void button9ActionPerformed(ActionEvent e) {
        	  if(button9.getText().equals(""))
              {
           	   if(Main.playerTurn==true)
           	   {
           		   button9.setText("X");
           		   Main.checkforwin();
           		   Main.playerTurn=false;
            	   }else
            	   {
            		   button9.setText("O");
            		   Main.checkforwin();
            		   Main.playerTurn=true;
            	   }
              }
        }
 
        public void initComponents() {
                // JFormDesigner - Component initialization - DO NOT MODIFY  //GEN-BEGIN:initComponents
                // Generated using JFormDesigner Evaluation license - Bradley Chelsey
                button1 = new JButton();
                button2 = new JButton();
                button3 = new JButton();
                button4 = new JButton();
                button5 = new JButton();
                button6 = new JButton();
                button7 = new JButton();
                button8 = new JButton();
                button9 = new JButton();
 
                //======== this ========
                setTitle("Tic Tac Toe");
                Container contentPane = getContentPane();
 
                //---- button1 ----
                button1.setText("");
                button1.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button1ActionPerformed(e);
                        }
                });
 
                //---- button2 ----
                button2.setText("");
                button2.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button2ActionPerformed(e);
                        }
                });
 
                //---- button3 ----
                button3.setText("");
                button3.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button3ActionPerformed(e);
                        }
                });
 
                //---- button4 ----
                button4.setText("");
                button4.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button4ActionPerformed(e);
                        }
                });
 
                //---- button5 ----
                button5.setText("");
                button5.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button5ActionPerformed(e);
                        }
                });
 
                //---- button6 ----
                button6.setText("");
                button6.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button6ActionPerformed(e);
                        }
                });
 
                //---- button7 ----
                button7.setText("");
                button7.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button7ActionPerformed(e);
                        }
                });
 
                //---- button8 ----
                button8.setText("");
                button8.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button8ActionPerformed(e);
                        }
                });
 
                //---- button9 ----
                button9.setText("");
                button9.addActionListener(new ActionListener() {
                        @Override
                        public void actionPerformed(ActionEvent e) {
                                button9ActionPerformed(e);
                        }
                });
 
                GroupLayout contentPaneLayout = new GroupLayout(contentPane);
                contentPane.setLayout(contentPaneLayout);
                contentPaneLayout.setHorizontalGroup(
                        contentPaneLayout.createParallelGroup()
                                .addGroup(contentPaneLayout.createSequentialGroup()
                                        .addContainerGap()
                                        .addGroup(contentPaneLayout.createParallelGroup()
                                                .addGroup(contentPaneLayout.createSequentialGroup()
                                                        .addComponent(button1, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                                        .addComponent(button2, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                                        .addComponent(button3, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE))
                                                .addGroup(contentPaneLayout.createSequentialGroup()
                                                        .addComponent(button4, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                                        .addComponent(button5, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                                        .addComponent(button6, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE))
                                                .addGroup(contentPaneLayout.createSequentialGroup()
                                                        .addComponent(button7, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                                        .addComponent(button8, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)
                                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                                        .addComponent(button9, GroupLayout.PREFERRED_SIZE, 68, GroupLayout.PREFERRED_SIZE)))
                                        .addContainerGap(11, Short.MAX_VALUE))
                );
                contentPaneLayout.setVerticalGroup(
                        contentPaneLayout.createParallelGroup()
                                .addGroup(contentPaneLayout.createSequentialGroup()
                                        .addContainerGap()
                                        .addGroup(contentPaneLayout.createParallelGroup(GroupLayout.Alignment.BASELINE)
                                                .addComponent(button1, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE)
                                                .addComponent(button2, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE)
                                                .addComponent(button3, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE))
                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                        .addGroup(contentPaneLayout.createParallelGroup(GroupLayout.Alignment.BASELINE)
                                                .addComponent(button4, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE)
                                                .addComponent(button5, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE)
                                                .addComponent(button6, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE))
                                        .addPreferredGap(LayoutStyle.ComponentPlacement.RELATED)
                                        .addGroup(contentPaneLayout.createParallelGroup(GroupLayout.Alignment.BASELINE)
                                                .addComponent(button7, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE)
                                                .addComponent(button8, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE)
                                                .addComponent(button9, GroupLayout.PREFERRED_SIZE, 55, GroupLayout.PREFERRED_SIZE))
                                        .addContainerGap(15, Short.MAX_VALUE))
                );
                pack();
                setLocationRelativeTo(getOwner());
                // JFormDesigner - End of component initialization  //GEN-END:initComponents
        }
 
        // JFormDesigner - Variables declaration - DO NOT MODIFY  //GEN-BEGIN:variables
        // Generated using JFormDesigner Evaluation license - Bradley Chelsey
        public JButton button1;
        public JButton button2;
        public JButton button3;
        public JButton button4;
        public JButton button5;
        public JButton button6;
        public JButton button7;
        public JButton button8;
        public JButton button9;
        private static final long serialVersionUID = 7526472295622776147L;
        // JFormDesigner - End of variables declaration  //GEN-END:variables
}




package Game;

import java.util.Scanner;

public class Main {
	public static boolean playerTurn=true;
	public static boolean playerWon=false;
	public static boolean computerWon=false;
	public static boolean playing=true;
	public static boolean playAgain=false;
	public static Scanner keyboard = new Scanner(System.in);
	
	public static tictactoe board= new tictactoe();
	
	public static void main (String[]args)
	{
		
			if (Main.board.isVisible() ==false)
			{
				Main.board.setVisible(true);
			}
	}
	
		public static void checkforwin()
		{
			if (board.button1.getText().equals("X"))
			{
				if (board.button4.getText().equals("X"))
				{
					if (board.button7.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button1.getText().equals("X"))
			{
				if (board.button5.getText().equals("X"))
				{
					if (board.button9.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button1.getText().equals("X"))
			{
				if (board.button2.getText().equals("X"))
				{
					if (board.button3.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button3.getText().equals("X"))
			{
				if (board.button5.getText().equals("X"))
				{
					if (board.button7.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button3.getText().equals("X"))
			{
				if (board.button6.getText().equals("X"))
				{
					if (board.button9.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button7.getText().equals("X"))
			{
				if (board.button8.getText().equals("X"))
				{
					if (board.button9.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button4.getText().equals("X"))
			{
				if (board.button5.getText().equals("X"))
				{
					if (board.button6.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button2.getText().equals("X"))
			{
				if (board.button5.getText().equals("X"))
				{
					if (board.button8.getText().equals("X"))
					{
						playerWon=true;
						computerWon=false;
						System.out.println("Player won!");
					}
				}
			}
			if (board.button1.getText().equals("O"))
			{
				if (board.button4.getText().equals("O"))
				{
					if (board.button7.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button1.getText().equals("O"))
			{
				if (board.button5.getText().equals("O"))
				{
					if (board.button9.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button1.getText().equals("O"))
			{
				if (board.button2.getText().equals("O"))
				{
					if (board.button3.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button3.getText().equals("O"))
			{
				if (board.button5.getText().equals("O"))
				{
					if (board.button7.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button3.getText().equals("O"))
			{
				if (board.button6.getText().equals("O"))
				{
					if (board.button9.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button7.getText().equals("O"))
			{
				if (board.button8.getText().equals("O"))
				{
					if (board.button9.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button4.getText().equals("O"))
			{
				if (board.button5.getText().equals("O"))
				{
					if (board.button6.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (board.button2.getText().equals("O"))
			{
				if (board.button5.getText().equals("O"))
				{
					if (board.button8.getText().equals("O"))
					{
						playerWon=false;
						computerWon=true;
						System.out.println("player 2 won!");
					}
				}
			}
			if (playerWon==true||computerWon==true)
			{
			board.setVisible(false);	
			System.out.println("would you like to play again true of false");
			playAgain=keyboard.nextBoolean();
			if (playAgain==true)
				{
					board.setVisible(false);
					board.button1.setText("");
					board.button2.setText("");
					board.button3.setText("");
					board.button4.setText("");
					board.button5.setText("");
					board.button6.setText("");
					board.button7.setText("");
					board.button8.setText("");
					board.button9.setText("");
					playerTurn=true;
					playerWon=false;
					computerWon=false;
					board.setVisible(true);
				}
			else
			{
				System.out.println("Thanks for playing ...........");
			}
			}
		}
	}

package Game;

public class changeclass {
	
}


