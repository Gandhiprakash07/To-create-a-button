import javax.swing.*;

public class MiniLogin {
    public static void main(String[] args) {
        JFrame f = new JFrame("Login Page");

        JTextField user = new JTextField("Username");
        JPasswordField pass = new JPasswordField("Password");
        JTextField email = new JTextField("Email ID");
        JTextField reg = new JTextField("Register No");
        JButton login = new JButton("Login");

        user.setBounds(50, 30, 200, 25);
        pass.setBounds(50, 65, 200, 25);
        email.setBounds(50, 100, 200, 25);
        reg.setBounds(50, 135, 200, 25);
        login.setBounds(100, 170, 100, 30);

        f.add(user); f.add(pass); f.add(email); f.add(reg); f.add(login);

        f.setSize(320,280);
        f.setLayout(null);
        f.setVisible(true);
        f.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
    }
}
