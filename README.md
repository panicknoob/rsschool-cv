package ka.it.hookah.dto;

import java.math.BigDecimal;
import java.util.List;

/**
 * Created by user on 03.06.2017.
 */
public class OrderDto extends AbstractDto {

    private Long createTime;

    private Long completedTime;

    private Integer tableId;

    private List<Integer> productIds;

    private List<Integer> personIds;

    private List<ProductDto> productDtos;

    private List<PersonDto> personDtos;

    private BigDecimal commonPrice;

    public Integer getTableId() {
        return tableId;
    }

    public void setTableId(Integer tableId) {
        this.tableId = tableId;
    }

    public Long getCreateTime() {
        return createTime;
    }

    public void setCreateTime(Long createTime) {
        this.createTime = createTime;
    }

    public Long getCompletedTime() {
        return completedTime;
    }

    public void setCompletedTime(Long completedTime) {
        this.completedTime = completedTime;
    }

    public List<Integer> getProductIds() {
        return productIds;
    }

    public void setProductIds(List<Integer> productIds) {
        this.productIds = productIds;
    }

    public BigDecimal getCommonPrice() {
        return commonPrice;
    }

    public void setCommonPrice(BigDecimal commonPrice) {
        this.commonPrice = commonPrice;
    }

    public List<Integer> getPersonIds() {
        return personIds;
    }

    public void setPersonIds(List<Integer> personIds) {
        this.personIds = personIds;
    }

    public List<ProductDto> getProductDtos() {
        return productDtos;
    }

    public void setProductDtos(List<ProductDto> productDtos) {
        this.productDtos = productDtos;
    }

    public List<PersonDto> getPersonDtos() {
        return personDtos;
    }

    public void setPersonDtos(List<PersonDto> personDtos) {
        this.personDtos = personDtos;
    }
}
