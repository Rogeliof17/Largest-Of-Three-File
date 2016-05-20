# Largest-Of-Three-File
finds the largest of three numbers from a file


public class BankAccountCopy
{
    public static void main(String[] args) {


        BankAccount account1 = new BankAccount(1000.0);

        BankAccount account2 = new BankAccount(account1);

        DecimalFormat dollar = new DecimalFormat("#,##0.00");


        System.out.println("Account #1 has a balance of $"
                            + dollar.format(account1.getBalance()));
        System.out.println("Account #2 has a balance of $"
                            + dollar.format(account2.getBalance()));


    }
}
