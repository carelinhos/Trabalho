public class Item {
    public int codigoProduto;
    public String nomeProduto;
    public int quantidadeProduto;
    public double valorProduto;

public Item (int codigoProduto,String nomeProduto,int quantidadeProduto,double valorProduto) {
    this.codigoProduto= codigoProduto;
    this.nomeProduto=nomeProduto;
    this.quantidadeProduto=quantidadeProduto;
    this.valorProduto=valorProduto;
}

    public String getNomeProduto() {
        return nomeProduto;
    }

    public void setNomeProduto(String nomeProduto) {
        this.nomeProduto = nomeProduto;
    }

    public int getCodigoProduto() {
        return codigoProduto;
    }

    public void setCodigoProduto(int codigoProduto) {
        this.codigoProduto = codigoProduto;
    }

    public int getQuantidadeProduto() {
        return quantidadeProduto;
    }

    public void setQuantidadeProduto(int quantidadeProduto) {
        this.quantidadeProduto = quantidadeProduto;
    }

    public double getValorProduto() {
        return valorProduto;
    }

}
public class Cliente {
   public int codigoCliente;
    private String nomeCliente;
    private String datacadastroCliente;
    private String CpfCnpj;

    public Cliente(int codigoCliente,String nomeCliente,String datacadastroCliente,String cpfCnpj) {
        this.codigoCliente=codigoCliente;
        this.nomeCliente=nomeCliente;
        this.datacadastroCliente=datacadastroCliente;
        this.CpfCnpj=cpfCnpj;
    }

    public int getCodigoCliente() {
        return codigoCliente;
    }

    public String getCpfCnpj() {
        return CpfCnpj;
    }

    public String getdatacadastroCliente() {
        return datacadastroCliente;
    }

    public String getNomeCliente() {
        return nomeCliente;
    }
}


public class Loja {
    private int codigoloja;
    private String nomeloja;
    private String Razaosocialloja;
    private String enderecoloja;

    public Loja(int codigoloja,String nomeloja,String razaosocialloja,String enderecoloja){
        this.codigoloja = codigoloja;
        this.nomeloja=nomeloja;
        this.Razaosocialloja=razaosocialloja;
        this.enderecoloja=enderecoloja;
    }

    public int getcodigoloja() {
        return codigoloja;
    }
    public String getEnderecoloja() {
        return enderecoloja;
    }

    public String getRazaosocialloja() {
        return Razaosocialloja;
    }

    public String getNomeloja() {
        return nomeloja;
    }
}

public class cupomfiscal {





    public static void main(String[] args){

        Cliente carlos = new Cliente(123, "Carlos", "18/20/2020", "123456");
        Loja mercado = new Loja(321, "Bahamas", "venda", "santaLuzia");
        Item banana = new Item(213, "banana", 10, 5.00);
        Item morango=new Item(456,"morango",20,6.00);

        System.out.println(carlos.getCodigoCliente());
        System.out.println(mercado.getcodigoloja());
        System.out.println(morango.getNomeProduto());
        System.out.println(banana.getNomeProduto());
        System.out.println(morango.getQuantidadeProduto());
        System.out.println(banana.getQuantidadeProduto());
        System.out.println(morango.getValorProduto());
        System.out.println(banana.getValorProduto());
        System.out.println("Total=" + (banana.getValorProduto() + morango.getValorProduto()));
    }





}


